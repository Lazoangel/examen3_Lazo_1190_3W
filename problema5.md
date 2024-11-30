print ("Lazo Jimenez Angel Jesus 3W")
class Agenda:
    def __init__(self):
        self.contactos = []
#Define cada una de las opciones si el usuario elige (añadir contactios)
    def añadir_contacto(self):
        nombre = input("Nombre: ")
        telefono = input("Telefono: ")
        email = input("Email: ")
        self.contactos.append({"nombre": nombre, "telefono": telefono, "email": email})
#Define cada una de las opciones si el usuario elige (lista de contactos)
    def lista_contactos(self):
        if self.contactos:
            for c in self.contactos:
                print(f"{c['nombre']}, {c['telefono']}, {c['email']}")
        else:
            print("No hay contactos.")
#Define cada una de las opciones si el usuario elige (buscar contactos)
    def buscar_contacto(self):
        nombre = input("Buscar nombre: ")
        for c in self.contactos:
            if c['nombre'].lower() == nombre.lower():
                print(f"{c['nombre']}, {c['telefono']}, {c['email']}")
                return
        print("Contacto no encontrado.")
#Define cada una de las opciones si el usuario elige (editar contacto)
    def editar_contacto(self):
        nombre = input("Editar nombre: ")
        for c in self.contactos:
            if c['nombre'].lower() == nombre.lower():
                c['nombre'] = input("Nuevo nombre: ")
                c['telefono'] = input("Nuevo telefono: ")
                c['email'] = input("Nuevo email: ")
                print("Contacto actualizado.")
                return
        print("Contacto no encontrado.")
#Define cada una de las opciones que pueden ser elegidas por el usuario 
def menu():
    agenda = Agenda()
    while True:
        print("\n1. Añadir contacto\n2. Lista de contactos\n3. Buscar contacto\n4. Editar contacto\n5. Cerrar")
        opcion = input("Seleccione opcion: ")
        if opcion == "1": agenda.añadir_contacto()
        elif opcion == "2": agenda.lista_contactos()
        elif opcion == "3": agenda.buscar_contacto()
        elif opcion == "4": agenda.editar_contacto()
        elif opcion == "5": break
        else: print("Opcion invalida.")

menu()
![image](https://github.com/user-attachments/assets/7646b673-6065-4966-867a-e4b2e1f6edf1)
![image](https://github.com/user-attachments/assets/899d3152-3a11-4094-aae6-f33e29c97926)
