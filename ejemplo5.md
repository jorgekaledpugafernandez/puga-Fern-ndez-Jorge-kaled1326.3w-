
![image](https://github.com/user-attachments/assets/2407fe8f-dccc-4525-ae0d-c18155935c5c)

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

