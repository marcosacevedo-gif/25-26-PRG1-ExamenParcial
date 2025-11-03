# Examen Parcial - alejandrohernandez200606-cloud

**Usuario GitHub:** alejandrohernandez200606-cloud
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 002, Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 8 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2af2b00b22b696ff40b21e2c9b472fc292598437/entregas/hernandezAlejandro/reto-003/edificio.java) (Reto 003)

```java
public class edificio {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2af2b00b22b696ff40b21e2c9b472fc292598437/entregas/hernandezAlejandro/reto-003/edificio.java) (Reto 003)

```java
String[][] edificio = new String[8][6];
// ...
for (int p = 1; p <= 7; p++) {
    for (int h = 0; h < HABITACIONES; h++) {
        // uso de edificio[p][h]
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2af2b00b22b696ff40b21e2c9b472fc292598437/entregas/hernandezAlejandro/reto-003/edificio.java) (Reto 003)

```java
boolean persianaAbierta = Math.random() < 0.7;
boolean luzEncendida = Math.random() < 0.6;

if (persianaAbierta) edificio[p][h] = "[ ]";
else edificio[p][h] = luzEncendida ? "[º]" : "[*]";
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Reto002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/cb6ea30d491d1c9eaf6a2e35d593244ede140537/entregas/HernandezAlejandro/Reto002.java) (Reto 002)

```java
if (energiaVampiro <= 0) {
    System.out.println("El heroe gana la batalla");
    break;
}
// ...
if (energiaHeroe <= 0) {
    System.out.println("El vampiro gana la batalla");
    break;
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2af2b00b22b696ff40b21e2c9b472fc292598437/entregas/hernandezAlejandro/reto-003/edificio.java) (Reto 003)

```java
for (int dia = 1; dia <= DIAS_SEMANA; dia++) {
    // ...
    for (int hora = 1; hora <= HORAS_DIA; hora++) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2af2b00b22b696ff40b21e2c9b472fc292598437/entregas/hernandezAlejandro/reto-003/edificio.java) (Reto 003, líneas 5-8)

```java
final int PLANTAS = 8;
final int HABITACIONES = 6;
final int HORAS_DIA = 24;
final int DIAS_SEMANA = 7;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2af2b00b22b696ff40b21e2c9b472fc292598437/entregas/hernandezAlejandro/reto-003/edificio.java) (Reto 003, líneas 15-17)

```java
Integer rayoColumna = null;
Integer plantaMantenimiento = null;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2af2b00b22b696ff40b21e2c9b472fc292598437/entregas/hernandezAlejandro/reto-003/edificio.java) (Reto 003, línea 82)

```java
if (rayoColumna != null && hora == 1)
```

¿Qué observas en este código?


