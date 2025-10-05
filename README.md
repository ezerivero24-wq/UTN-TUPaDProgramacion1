# UTN-TUPaDProgramacion1

#Actividad 1
print("Hola Mundo");

#Actividad 2

nombre = input("Ingrese su nombre: ")

print(f"¡Hola {nombre}!")


#Actividad 3

nombre = input("Ingrese su nombre: ")
apellido = input("Ingrese su apellido: ")
edad = input("Ingrese su edad: ")
residencia = input("Ingrese su lugar de residencia: ")

print(f"Soy {nombre} {apellido}, tengo {edad} años y vivo en {residencia}.")


#Actividad 4

radio = float(input("Ingrese el radio del círculo: "))

pi = 3.1416

area = pi * radio ** 2
perimetro = 2 * pi * radio

print(f"El área del círculo es: {area:}")
print(f"El perímetro del círculo es: {perimetro:}")


#Actividad 5

segundos = int(input("Ingrese la cantidad de segundos: "))

horas = segundos / 3600  

print(f"{segundos} segundos equivalen a {horas:} horas.")


#Actividad 6

numero = int(input("Ingrese un número: "))

print(f"Tabla de multiplicar del {numero}:")

for i in range(1, 11):
    print(f"{numero} x {i} = {numero * i}")


#Actividad 7

numero1 = int(input("Ingrese el primer número (distinto de 0): "))
numero2 = int(input("Ingrese el segundo número (distinto de 0): "))

suma = numero1 + numero2
resta = numero1 - numero2
multiplicacion = numero1 * numero2
division = numero1 / numero2  

print(f"Suma: {suma}")
print(f"Resta: {resta}")
print(f"Multiplicación: {multiplicacion}")
print(f"División: {division}")


#Actividad 8

peso = float(input("Ingrese su peso en kg: "))
altura = float(input("Ingrese su altura en metros: "))

imc = peso / (altura ** 2)

print(f"Su índice de masa corporal (IMC) es: {imc:}")


#Actividad 9

# Pedir al usuario la temperatura en Celsius
celsius = float(input("Ingrese la temperatura en grados Celsius: "))

# Convertir a Fahrenheit
fahrenheit = (9/5) * celsius + 32

# Mostrar el resultado
print(f"{celsius}°C equivalen a {fahrenheit:}°F")


#Actividad 10


numero1 = float(input("Ingrese el primer número: "))
numero2 = float(input("Ingrese el segundo número: "))
numero3 = float(input("Ingrese el tercer número: "))

promedio = (numero1 + numero2 + numero3) / 3

print(f"El promedio de los números ingresados es: {promedio:}")
