# Examen Parcial - DaniArroyo07

**Usuario GitHub:** DaniArroyo07
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 10 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `HotelLuces.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/0940bca38a3852dfc71939340aea56c2d6eddd4b/entregas/arroyosanchezdaniel/HotelLuces.java) (Reto 003)

```java
final String VENTANA_CERRADA = ":[ ]:";
final String LUZ_APAGADA = ":[º]:";
final String LUZ_ENCENDIDA = ":[*]:";
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `HotelLuces.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/0940bca38a3852dfc71939340aea56c2d6eddd4b/entregas/arroyosanchezdaniel/HotelLuces.java) (Reto 003)

```java
for (dia = 1; dia <= 6; dia++) {
    int consumoPorDía = 0;
    for (horas = 0; horas < 24; horas++) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `HotelLuces.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/0940bca38a3852dfc71939340aea56c2d6eddd4b/entregas/arroyosanchezdaniel/HotelLuces.java) (Reto 003)

```java
if (probVentanaAbierta >= 0.7) {
    if (numeroHabitaciones != 4) {
        System.out.print(VENTANA_CERRADA);
    }
} else if (probVentanaAbierta < 0.7 && probLuzEncendida >= 0.6) {
    if (numeroHabitaciones != 4) {
        System.out.print(LUZ_APAGADA);
    }
} else if (probVentanaAbierta < 0.7 && probLuzEncendida < 0.6) {
    if (numeroHabitaciones != 4) {
        System.out.print(LUZ_ENCENDIDA);
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `HotelLuces.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/0940bca38a3852dfc71939340aea56c2d6eddd4b/entregas/arroyosanchezdaniel/HotelLuces.java) (Reto 003)

```java
for (plantas = 7; plantas >= PLANTA_BAJA; plantas--) {
    for (numeroHabitaciones = 1; numeroHabitaciones <= 7; numeroHabitaciones++) {
        // ...
    }
    System.out.print(SEPARADOR + "P" + plantas);
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `HotelLuces.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/0940bca38a3852dfc71939340aea56c2d6eddd4b/entregas/arroyosanchezdaniel/HotelLuces.java) (Reto 003)

```java
System.out.println("Día: " + dia + ". Hora: " + horas);
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3ADaniArroyo07+is%3Aall) (Reto 003, línea 4)

```java
final double PERSIANA_CERRADA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3ADaniArroyo07+is%3Aall) (Reto 003, línea 10)

```java
final String separador = "[    ]";
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3ADaniArroyo07+is%3Aall) (Reto 003, línea 1)

```java
public class edificio {
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3ADaniArroyo07+is%3Aall) (Reto 003, líneas 15-16)

```java
for (int fila = 1; fila <= 7; fila++) {
    for (int columna = 1; columna <= 6; columna++) {
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3ADaniArroyo07+is%3Aall) (Reto 003, línea 19)

```java
System.out.print(!abierta ? VENTANA_CERRADA: encendida ? VENTANA_CON_LUZ_ENCENDIDA : VENTANA_CON_LUZ_APAGADA);
```

¿Qué observas en este código?

