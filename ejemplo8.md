
![image](https://github.com/user-attachments/assets/312a31a5-50f6-4164-8ed0-de268b200a86)

def superposicion(lista1, lista2):
    for elem1 in lista1:
        for elem2 in lista2:
            if elem1 == elem2:
                return True
    return False

# Ejemplo de uso
lista1 = [1, 2, 3, 4, 5]
lista2 = [5, 6, 7, 8, 9]
print(superposicion(lista1, lista2))  # Debería devolver True

lista3 = ['a', 'b', 'c']
lista4 = ['x', 'y', 'z']
print(superposicion(lista3, lista4))  # Debería devolver False
