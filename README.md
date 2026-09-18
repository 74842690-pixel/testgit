# Calculadora de estadísticas básicas

print("=== CALCULADORA DE ESTADÍSTICAS ===")

entrada = input("Ingresa los números separados por espacios: ")

numeros = [float(numero) for numero in entrada.split()]

cantidad = len(numeros)
suma = sum(numeros)
promedio = suma / cantidad
minimo = min(numeros)
maximo = max(numeros)

print("\n=== RESULTADOS ===")
print("Cantidad:", cantidad)
print("Suma:", suma)
print("Promedio:", promedio)
print("Mínimo:", minimo)
print("Máximo:", maximo)
