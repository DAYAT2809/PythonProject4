def buscar_valor(matriz, valor):
    for i in range(len(matriz)):
        for j in range(len(matriz[i])):
            if matriz[i][j] == valor:
                return "Valor {valor} encontrado en la posición ({i}, {j})"
    return "Valor {valor} no encontrado en la matriz."

# Ejemplo de uso
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]

]

valor_a_buscar = 5
resultado = buscar_valor(matriz, valor_a_buscar)
print(resultado)
