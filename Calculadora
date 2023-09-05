"""Hecho por Antonio Valdés Hernández"""
import time

inicio=time.time()

n1=int(input("Ingresa un número: "))
n2=int(input("Ingresa otro número: "))

quehacer = 0
while quehacer != 6:
    print("""
        ¿Qué operación desea realizar? 
        1] Suma
        2] Resta
        3] Multiplicación
        4] División   
        5] Cambiar Números
        6] Salir
        """)

    quehacer=int(input())
    if quehacer==1:
        print(" ")
        print("Resultado: ",n1," + ",n2," = ",n1+n2)

    if quehacer==2:
        print(" ")
        print("Resultado: ",n1," - ",n2," = ",n1-n2)

    if quehacer==3:
        print(" ")
        print("Resultado: ",n1," * ",n2," = ",n1*n2)

    if quehacer==4:
        print(" ")
        print("Resultado: ",n1," / ",n2," = ",n1/n2)

    if quehacer==5:
        n1=int(input("Ingresa un número: "))
        n2=int(input("Ingresa otro número: "))

fin=time.time()
tiempofin=fin-inicio
print(f"El tiempo total de ejecución fue: {tiempofin:5f} segundos uwu")
