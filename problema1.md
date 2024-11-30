print ("Lazo Jimenez Angel Jesus 3W")
class Alumno:
    def __init__(self, nombre, nota): #Esta linea es para definir 
        self.nombre = nombre #Se define el nombre
        self.nota = nota #Se define la calificacion

    def imprimir_datos(self): 
        print(f"Nombre del alumno: {self.nombre}") #Imprime el nombre de el usuario
        print(f"Nota: {self.nota}") #Imprime la nota del usuario

    def resultado(self): 
        if self.nota >= 6: #Si es mayor o igual a 6 aprobaste y si no reprobaste
            print(f"{self.nombre} a aprobado") #Imprime el mensaje de aprobado
        else:
            print(f"{self.nombre} a reprobado") #Imprime el mensaje de reprobado


alumno1 = Alumno("Lazo Jimenez", 6.7) #Imprime el nombre del alumno y su calificacion
alumno1.imprimir_datos()
alumno1.resultado()

alumno2 = Alumno("Salas de la O", 5.6) #Imprime el nombre del alumno y su calificacion
alumno2.imprimir_datos()
alumno2.resultado()
![image](https://github.com/user-attachments/assets/e1732e62-2760-412e-bcce-97c6b2a99044)
![image](https://github.com/user-attachments/assets/a5550614-3a7b-4b57-9d4d-583d017bd5b4)
