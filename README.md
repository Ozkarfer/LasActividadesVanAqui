# LasActividadesVanAqui
#A2: Ejercicios Básicos en Python
#Oscar Fernando Morales Bueno
#1412211
print("Bienvenido, como puedo referirme a usted? ")
nombre = input()
A = ['Ana','ana', 'Pedro','pedro', 'Juan','juan'] 
if nombre in A:
  print("No lo tomes a mal, pero podemos usar otro?")
else: 
  print("Okai gracias, ",nombre)


#A2: Ejercicios Básicos en Python
#Oscar Fernando Morales Bueno
#1412211
lista = [50, 40, 30, 20, 10]

def invertir_lista(lista):
  if lista == []:
    inversa = lista
  else:
    inversa = [lista[-1]] + invertir_lista(lista[:-1])
  return inversa  
print(invertir_lista(lista))
    
