
![image](https://github.com/user-attachments/assets/7650d0e6-818f-422e-8a06-5cea95e8350b)

def longitud(secuencia):
    contador = 0
    for elemento in secuencia:
        contador += 1
    return contador

# Ejemplos de uso
cadena = "Hola, mundo"
lista = [1, 2, 3, 4, 5]

print(f"La longitud de la cadena '{cadena}' es {longitud(cadena)}.")
print(f"La longitud de la lista {lista} es {longitud(lista)}.")
