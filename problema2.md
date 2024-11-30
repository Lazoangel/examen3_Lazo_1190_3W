print("Lazo Jimenez Angel Jesus 3W")
class Persona:
    def __init__(self, nombre, edad): #define el nombre y la edad de los usuarios
        self.nombre = nombre
        self.edad = edad

    def mostrar_datos(self): #muestra los datos de nombre y edad en pantala
        print(f"Nombre: {self.nombre}")
        print(f"Edad: {self.edad}")

    def es_mayor_de_edad(self): #imprime segun si es mayo de 18 o menor
        if self.edad >= 18:
            print(f"{self.nombre} es mayor de edad")
        else:
            print(f"{self.nombre} es menor de edad")

persona1 = Persona("David Ramirez", 16) #Imprime el mensaje completo con los datos del usuario
persona1.mostrar_datos()
persona1.es_mayor_de_edad()

persona2 = Persona("Carlos Ramirez", 24) #Imprime el mensaje completo con los datos del usuario
persona2.mostrar_datos()
persona2.es_mayor_de_edad()
![image](https://github.com/user-attachments/assets/05a28788-f3d6-44e0-a082-424f3fe307dd)
![image](https://github.com/user-attachments/assets/bc2a24ec-c29a-44a4-bc28-3ec94903e629)
