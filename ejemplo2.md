![image](https://github.com/user-attachments/assets/3270f47f-38cb-4a0f-8fec-ba09847a471c)

def max_de_tres(num1, num2, num3):
    if num1 >= num2 and num1 >= num3:
        return num1
    elif num2 >= num1 and num2 >= num3:
        return num2
    else:
        return num3

# Ejemplo de uso
numero1 = 10
numero2 = 20
numero3 = 15
resultado = max_de_tres(numero1, numero2, numero3)
print(f"El mayor de {numero1}, {numero2} y {numero3} es {resultado}.")

