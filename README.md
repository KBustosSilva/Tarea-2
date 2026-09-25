# Tarea 2 

## Problema 1: Clasificador de temperatura

* Este código despliega las temperaturas con la función de range(-30, 51) para recorrer los números desde -30 hasta 50. 

* En cada criterio,  if, elif y else evalúan el valor de la temperatura y le asignan una categoría: "Muy frío", "Templado" o "Caluroso". 

* Decidí incluir el número junto con su categoría en el print() para poder identificar qué temperatura está siendo evaluada.

* Como resultado, se despliega una lista: 1. los valores del -30 al -1 aparecen acompañados de "Muy frío"; 2. los valores del 0 al 24 aparecen con "Templado"; 3. los valores del 25 al 50 aparecen con "Caluroso".

## Problema 2: Números especiales del robot

* Este código los números con range(1, 101) para recorrer los números del 1 al 100. 

* Para comprobar la divisibilidad se utiliza el operador módulo %. Primero se revisa si el número es divisible por 10 y, si no lo es, se comprueba si es divisible por 5. Decidí utilizar este orden ya que todos los números divisibles por 10 también son divisibles por 5.

* Como resultado, los múltiplos de 10 aparecen acompañados de "Bip Bip", mientras que los demás múltiplos de 5 aparecen acompañados de "Bip".

## Problema 3: Detector de puntaje gamer

* Este código utiliza input() para solicitar al usuario dos puntajes y int() para convertir los valores ingresados en números enteros.

* Luego, ambos puntajes se suman y el resultado se guarda en la variable suma. 

* Utilicé if, elif y else para separar los tres niveles según el resultado obtenido.

* Como resultado, la salida depende de los valores ingresados por el usuario. Si la suma es menor a 50, se muestra "Resultado: Nivel principiante". Si la suma está entre 50 y 79, se muestra "Resultado: Nivel intermedio", y si es igual o superior a 80, se muestra "Resultado: Nivel pro".

## Problema 4: Calculador de perfil musical

* Este código utiliza input() para solicitar la edad del usuario y sus respuestas sobre si le gusta la música y bailar. 

* La edad se convierte a un número entero mediante int(), mientras que las respuestas sobre los gustos se convierten en valores booleanos (True o False) mediante una comparación con la respuesta "si". 

* Utilicé los operadores lógicos and y not para evaluar las distintas combinaciones de edad y preferencias.

* Como resultado, el programa muestra uno de tres mensajes dependiendo de las respuestas del usuario: 1. si tiene 18 años o más, le gusta la música y le gusta bailar, muestra "Eres una estrella de la fiesta"; 2. si le gusta la música pero no bailar, muestra "Te gusta la música, pero no tanto bailar"; 3. en cualquier otro caso, muestra "Tienes tu propio estilo".