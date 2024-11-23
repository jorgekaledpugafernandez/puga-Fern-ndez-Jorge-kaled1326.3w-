![image](https://github.com/user-attachments/assets/5529dbc8-f4c3-469a-a03b-88786f3dc464)

def es_palindromo(palabra):
    # Convertir la palabra a minúsculas y eliminar espacios
    palabra = palabra.lower().replace(" ", "")
    # Comparar la palabra con su inversa
    return palabra == palabra[::-1]

# Ejemplo de uso
print(es_palindromo("radar"))  # Debería devolver True
print(es_palindromo("hola"))   # Debería devolver False
print(es_palindromo("Ana"))    # Debería devolver True

