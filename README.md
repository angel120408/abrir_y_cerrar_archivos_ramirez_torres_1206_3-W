# Codigo Creado En Clase

archivo=open("ramirez_1206_3°W.txt","r")
print(archivo.readable())


archivo.close()

![image](https://github.com/user-attachments/assets/93841ff6-70b8-4d1d-afb6-b7e0ba33f46b)
![image](https://github.com/user-attachments/assets/3bc0020e-e819-4b87-a06d-1245c7ff0ce7)

# Codigo Hecho Con Lo Que Se Mando A Classroom 

print("Primera parte")
a = open("archivo de practica.txt","r")
print(a.read())

a.close()

print(" ")
print("Segunda parte")
f = open("archivo de practica.txt","r")
print(f.read( 5))
print(f.read(15))
print(f.read(20))


f.close()

print(" ")
#print("Tercera parte")

f = open("archivo de practica.txt","a")
f.write("Al archivo ahora es masgrande")

f.close()

f = open("archivo de practica.txt","r")
print(f.read())

f.close()

print(" ")
print("ejemplo #6")

f = open("archivo de practica.txt","w")
f.write("Se elimino el contenido")

f.close()

print("Ejemplo #7")

import os
os.remove("archivo de practica.txt")

print("Ejemplo #8")

import os
if os.path.exists("archivo de practica.txt"):
    os.remove("archivo de practica.txt")
else:
    print("Ya no existe el archivo")

print("Ejemplo #9")

import os
os.rmdir("archivo de practica.txt")


![image](https://github.com/user-attachments/assets/f6139981-f552-4148-8de1-b2d80bf5cb3f)
![image](https://github.com/user-attachments/assets/65735e6e-8ff7-43e1-89d5-95c9e19880c0)
![image](https://github.com/user-attachments/assets/6fcd3e01-94a9-4d59-a82d-bec669c24e07)



