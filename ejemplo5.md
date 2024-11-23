![image](https://github.com/user-attachments/assets/b30b142a-f423-423f-9187-c148444ca8dc)
def sum(numeros):
    resultado = 0
    for numero in numeros:
        resultado += numero
    return resultado

def multip(numeros):
    resultado = 1
    for numero in numeros:
        resultado *= numero
    return resultado

# Ejemplos de uso
numeros = [1, 2, 3, 4]
print(f"La suma de {numeros} es {sum(numeros)}.")  # Debería devolver 10
print(f"La multiplicación de {numeros} es {multip(numeros)}.")  # Debería devolver 24

