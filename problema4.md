print ("Lazo Jimenez Angel Jesus 3W")
class Calculadora:
    def __init__(self, num1, num2): #define num1 y num2
        self.num1 = num1
        self.num2 = num2
#Define cada una de las opciones (suma, resta, multiplicacion y division)
    def suma(self):
        return self.num1 + self.num2

    def resta(self):
        return self.num1 - self.num2

    def multiplicacion(self):
        return self.num1 * self.num2

    def division(self):
            return self.num1 / self.num2
#Le pide al usuario que ingrese los numeros necesarios
num1 = int(input("Ingrese el primer numero: "))
num2 = int(input("Ingrese el segundo numero: "))

calculadora = Calculadora(num1, num2)
#Imprime cada una de las opciones
print(f"La suma es: {calculadora.suma()}")
print(f"La resta es: {calculadora.resta()}")
print(f"La multiplicacion es: {calculadora.multiplicacion()}")
print(f"La division es: {calculadora.division()}")
![image](https://github.com/user-attachments/assets/a3da79d7-e35b-4778-96fa-189f8e9256f3)
![image](https://github.com/user-attachments/assets/1a102554-ff3d-4b41-841f-775ed3ad7109)
