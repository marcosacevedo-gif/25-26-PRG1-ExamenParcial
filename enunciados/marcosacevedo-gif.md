# Examen Parcial - marcosacevedo-gif

**Usuario GitHub:** marcosacevedo-gif
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Ejercicios, Reto 001, Reto 002, Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 10 preguntas (en función a lo indicado en el examen).


---

## Pregunta 1

Archivo: `ClasificacionEdades.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/ClasificacionEdades.java) (Ejercicios)

```java
if (edad < EDAD_INFANCIA) {
    // ...
} else if (edad < EDAD_ADOLESCENCIA && edad > EDAD_NIÑO) {
    // ...
} else if (edad < EDAD_JOVEN && edad > EDAD_INFANCIA) {
    // ...
}
```

¿Qué observas en este código?
## RESPUESTA

La observación sobre el problema propuesto se refiere a las condiciones que determinan los rangos de edad dentro de las sentencias if y else if.

En concreto, trata sobre cómo se están comparando los valores de la variable edad con las constantes (EDAD_NIÑO, EDAD_INFANCIA, EDAD_ADOLESCENCIA, EDAD_JOVEN) para clasificar correctamente las etapas de vida.

El problema está en el uso de los operadores, específicamente en las condiciones del tipo edad > EDAD_INFANCIA o edad > EDAD_NIÑO. Estos rangos dejan fuera ciertos valores, como cuando edad es exactamente igual a una de las constantes.
Por ejemplo, si edad = 6, no entraría en el bloque de infancia porque no cumple edad > EDAD_NIÑO (0) y tampoco edad < EDAD_INFANCIA (6).
Esto causa un problema de exclusión de límites, ya que algunas edades no se clasifican correctamente.

Para solucionar esto, se deben incluir los valores límites usando operadores mayores o iguales (>=) y menores o iguales (<=) según corresponda. un ejemplo seria:
 if (edad >= EDAD_MINIMA && edad < EDAD_INFANCIA) {
    System.out.println("Usted es un niño");
}
else if (edad >= EDAD_INFANCIA && edad < EDAD_ADOLESCENCIA) {
    System.out.println("Usted está en la infancia");


---

## Pregunta 2

Archivo: `PiedraPapelTijera.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/PiedraPapelTijera.java) (Ejercicios)

```java
class juego {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?
## RESPUESTA
Observamos que se trata del inicio del código "PiedraPapelTijera.java" 

El problema está en el nombre de la clase y en la estructura incompleta del código.
En Java, las clases deben seguir ciertas normas de nomenclatura y estructura para que el programa sea claro y correcto.

El error no es de código ya que el código funciona, pero sí es un error de syntaxis en Java.

En Java, los nombres de las clases deben empezar por mayúscula según las normas de escritura recomendadas (CamelCase).

Por tanto, class juego debería escribirse como class Juego.

Además, el código inicial no tenía contenido dentro del método main, por lo que no hacía nada era solo una estructura vacía.

La solución principal a este problema sería cambiar "juego" por "Juego"
o directamente cambiar el nombre de la clase a PiedraPapelTijera ya que sino no quedaria claro que estamos haciendo ya que Juego es muy general.
---

## Pregunta 3

Archivo: `CalcularPrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-001/CalcularPrecioFinal.java) (Reto 001)

```java
// entrada de datos -> cálculo -> salida
// (usa variables como precioBaseCentimos, cantidad, iva y descuentos escalonados)
```

¿Qué observas en este código?
## RESPUESTA

En este problema de aqui en realidad no se ve un fallo de código como tal sino que "// entrada de datos -> cálculo -> salida
// (usa variables como precioBaseCentimos, cantidad, iva y descuentos escalonados)". Es utilizado como una especie de guía dentro del código, es decir, no interfiere y no es un problema como tal. Sino más bien un comentario de java 

Este comentario es normalmente usado en códigos creados por una IA ya que estos comentarios son usados como guía por la persona que lo preguntó

La solución a este problema es sencilla y es basicamente borrar estos comentarios ya que el programa al ejecutarse lo ignora completamente.


---

## Pregunta 4

Archivo: `BatallaHeroeVampirosextendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-002/BatallaHeroeVampirosextendido.java) (Reto 002)

```java
int opcion = scanner.nextInt();
int ataqueHeroe = 0;
double probExitoHeroe = 0.0;
if (opcion == 1) { ataqueHeroe = 7; probExitoHeroe = 0.5; }
else if (opcion == 2) { ataqueHeroe = 15; probExitoHeroe = 0.25; }
else if (opcion == 3) { ataqueHeroe = 30; probExitoHeroe = 0.12; }
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-003/edificio.java) (Reto 003)

```java
for (int hora=0; hora<=24; hora++) {
    System.out.println("Son las " +  hora + " del dia " + dia);
    for (int planta=1; planta<=7; planta++) {
        for (int columna=1; columna<=6; columna++) {
            abierta = Math.random() < PERSIANA_ABIERTA;
            encendida = Math.random() < LUZ_ENCENCIDA;
            System.out.println(!abierta ? VENTANA_CERRADA : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
            if (columna == 3 ) {
                System.out.print( SEPARADOR );
            }
        }
    }
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `ClasificacionEdades.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/ClasificacionEdades.java) (Reto 003)

```java
else if (edad < EDAD_ADOLESCENCIA && edad > EDAD_NIÑO) {
    System.out.println("Usted está en la infancia");
}
else if (edad < EDAD_JOVEN && edad > EDAD_INFANCIA) {
    System.out.println("Usted es un adolescente");
}
else if (edad < EDAD_ADULTO && edad > EDAD_ADOLESCENCIA) {
    System.out.println("Usted es un joven");
}
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `GeneradorRandomNumeros.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/Prog1/retos/GeneradorRandomNumeros.java) (Reto 003)

```java
int numeroAleatorio=(int) (Math.random()*100)+1;
System.out.println("Introduce la cantidad de números aleatorios a generar:");

for (int i = 0; i < 10; i++) {
    numeroAleatorio = (int) (Math.random() * 100) + 1;
    System.out.println(numeroAleatorio);
}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `ConvertirDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-001/ConvertirDuracion.java) (Reto 001)

```java
int segundosTotales;
int dias, horas, minutos, segundos;

System.out.println("¿Cuántos segundos desea convertir?");
segundosTotales = teclado.nextInt();

dias = segundosTotales / 86400;
segundosTotales = segundosTotales % 86400;

horas = segundosTotales / 3600;
segundosTotales = segundosTotales % 3600;
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `BatallaHeroeVampirosbase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-002/BatallaHeroeVampirosbase.java) (Reto 002)

```java
int vidaVampiro = 10;
final double PORCENTAJE_EXITO_VAMPIRO = 0.5;
final int DAÑO_ESPADA = 2;

int vidaGuerrero = 10;
final double PORCENTAJE_EXITO_GUERRERO = 0.5;
final int DAÑO_MORDIDA = 4;
```

¿Qué observas en este código?
## RESPUESTA

La observación que podemos llegar a ver se refiere a la forma en que están declaradas las variables y constantes relacionadas con el vampiro y el guerrero.
En concreto, parece no estar claro el intercambio de nombres y valores entre las variables de daño y los personajes.
Esto puede generar confusión en la lectura y mantenimiento del código, ya que las constantes no están agrupadas según el personaje que las usa.

Por ello no se puede considerar un error de código ya que si lo ejecutas va perfectamente y hace su finalidad, sino que es más bien un error de sintaxis pudiendo confundir a una persona que quiera entender el código.
Por lo tanto la solución a dar es cambiar el nombre de las variables y el erro quedaría correjido así: 
int vidaGuerrero = 10;
final double PORCENTAJE_EXITO_GUERRERO = 0.5;
final int DAÑO_ESPADA = 2;

int vidaVampiro = 10;
final double PORCENTAJE_EXITO_VAMPIRO = 0.5;
final int DAÑO_MORDIDA = 4;

---

## Pregunta 10

Archivo: `PiedraPapelTijera.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/PiedraPapelTijera.java) (Reto 003)

```java
int ordenador = (int) (Math.random() * 3) + 1;
System.out.println("El ordenador ha elegido: " + ordenador);
```
## RESPUESTA
la observación es cómo se genera y muestra la elección del ordenador, es decir, la parte donde el programa decide aleatoriamente si el ordenador elige piedra, papel o tijera.

El código no tiene un error de ejecución, ya que funciona y genera un número aleatorio entre 1 y 3 correctamente.
Sin embargo, el problema está en la forma en que se muestra el resultado:
cuando se imprime System.out.println("El ordenador ha elegido: " + ordenador);, el usuario solo ve un número (1, 2 o 3), pero no sabe si eso significa piedra, papel o tijera.

Esto dificulta la comprensión del resultado, ya que el programa no traduce el número a su opción correspondiente.

La corrección consiste en mostrar el nombre de la jugada (piedra, papel o tijera) en lugar del número.
Podemos hacerlo con una estructura if o switch:
int ordenador = (int) (Math.random() * 3) + 1;
String eleccionOrdenador = "";

if (ordenador == PIEDRA) {
    eleccionOrdenador = "piedra";
} else if (ordenador == PAPEL) {
    eleccionOrdenador = "papel";
} else {
    eleccionOrdenador = "tijera";
}

System.out.println("El ordenador ha elegido: " + eleccionOrdenador);


¿Qué observas en este código?


