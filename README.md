import random
# numeros
# lower case 
# uppercase
# symbols

print("|----------------------|")
print("|--PASSWORD GENERATOR--|")
print("|----------------------|")
print("\n")

# characters = int(input("# Of characters for your password? (8 or +): "))

def create_number ():
    return str(random.randint(0,9))   

def create_lower_letter():
    letters = "abcdefghijklmnñopqrstuvwxyz" 
    i = random.randint(0, (len(letters)-1))
    return letters[i]


Muy buenas noches estimada Docente indico lo siguiente:
El lenguaje de Programación es Python
La version es Python 3.13.5
Las librerias usadas son: random string
El Programa seleccionado es un Generador seguro de Contraseñas
