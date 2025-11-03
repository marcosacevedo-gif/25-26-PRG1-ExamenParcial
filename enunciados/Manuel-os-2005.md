# Examen Parcial - Manuel-os-2005

**Usuario GitHub:** Manuel-os-2005
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 9 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `CalculadoraDePrecio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/CalculadoraDePrecio.java) (Reto 001)

```java
double descuento=0;
descuento=(unidades<10?0:(unidades<50?0.05:(unidades<100?0.10:0.15)));
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `DevolucionCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/DevolucionCambio.java) (Reto 001)

```java
int billetes=cambio/100;
int resto=cambio%100;
// ...
System.out.println(billetes+" monedas de 1");
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `ConversorDeDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/ConversorDeDuracion.java) (Reto 001)

```java
int dias=segundos/SEGUNDOS_POR_DIA;
int resto=segundos%SEGUNDOS_POR_DIA;
int horas=resto/SEGUNDOS_POR_HORA;
resto=resto%SEGUNDOS_POR_HORA;
int minutos=resto/SEGUNDOS_POR_MINUTO;
resto=resto%SEGUNDOS_POR_MINUTO;
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Reto_002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/Reto_002.java) (Reto 002)

```java
boolean vampiroVivo = true;
// ...
vampiroVivo = vidaVampiro <= 0;
if (vampiroVivo) {
    // turno del vampiro
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Reto_002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/Reto_002.java) (Reto 002)

```java
final int ATAQUE_1 = 7;
final double ATAQUE_PROBABILIDAD_1 = 0.5;
// ...
final int ATAQUE_3 = 30;
final double ATAQUE_PROBABILIDAD_3 = 0.12;
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `DevolucionCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/DevolucionCambio.java) (Reto 001)

```java
billetes=resto/2;
resto=resto%2;
System.out.println(billetes+" monedas de 2");

System.out.println(billetes+" monedas de 1");
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Reto_002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/Reto_002.java) (Reto 002)

```java
vampiroVivo = vidaVampiro <= 0;

if (vampiroVivo) {
    int ataque = (int) (Math.random() * 3) + 1;
    if (ataque == 1) {
        if (Math.random() < ATAQUE_PROBABILIDAD_1) {
            vidaVampiro = vidaVampiro - ATAQUE_1;
            System.out.println("El vampiro recibe daño");
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Reto_002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/Reto_002.java) (Reto 002)

```java
final int DAÑO_ESPADA = 2;
int vidaGuerrero = 20;
final double PORCENTAJE_EXITO_GUERRERO = 0.5;

// Estas constantes nunca se usan en el código
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `CalculadoraDePrecio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1876fbf4f06a47bf6d7997067adf1984538ee87c/evaluaciones/retos/CalculadoraDePrecio.java) (Reto 001)

```java
System.out.println("Descuento aplicado: "+(descuento*100+"%"));
```

¿Qué observas en este código?


