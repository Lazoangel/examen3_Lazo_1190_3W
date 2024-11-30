print ("Lazo Jimenez Angel Jesus 3W")
class Triangulo:
    def __init__(self, lado1, lado2, lado3): #define los lados 1,2 y 3 

        self.lado1 = lado1
        self.lado2 = lado2
        self.lado3 = lado3

    def imprimir_lado_mayor(self): #Imprime el lado mayor del triangulo
        mayor = max(self.lado1, self.lado2, self.lado3)
        print(f"El lado mayor es: {mayor}")

    def tipo_triangulo(self): #Depende el tamaño de los lados pone el tipo de triangulo
        if self.lado1 == self.lado2 == self.lado3:
            print("El triangulo es equilatero")
        elif self.lado1 == self.lado2 or self.lado1 == self.lado3 or self.lado2 == self.lado3:
            print("El triangulo es isoceles")
        else:
            print("El triangulo es escaleno.")

triangulo1 = Triangulo(5, 5, 5) #Imrpime los datos del triangulo
triangulo1.imprimir_lado_mayor()
triangulo1.tipo_triangulo()

triangulo2 = Triangulo(7, 5, 7) #Imrpime los datos del triangulo
triangulo2.imprimir_lado_mayor()
triangulo2.tipo_triangulo()

triangulo3 = Triangulo(3, 4, 5) #Imrpime los datos del triangulo
triangulo3.imprimir_lado_mayor()
triangulo3.tipo_triangulo()
![image](https://github.com/user-attachments/assets/7692d9ee-4c2c-467b-a914-1a1a9d2f3afd)
![image](https://github.com/user-attachments/assets/0f09bf56-de7e-47cd-80d7-ca4a8c6c4c5d)
