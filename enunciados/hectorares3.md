# Examen Parcial - hectorares3

**Usuario GitHub:** hectorares3
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 003

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

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
class SimulacionHotel {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
if (!hayRayo && random.nextDouble() < PROB_RAYO) {
    hayRayo = true;
    columnaRayo = 1 + random.nextInt(HABITACIONES);
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
boolean persianaAbierta = random.nextDouble() < PROB_PERSIANA;
boolean luzEncendida = random.nextDouble() < PROB_LUZ;
if (persianaAbierta && luzEncendida) {
    celda = SIMBOLO_PERSIANA_LUZ;
} else if (persianaAbierta) {
    celda = SIMBOLO_PERSIANA;
} else {
    celda = SIMBOLO_VACIO;
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
if (SIMBOLO_PERSIANA_LUZ.equals(celda)) {
    consumoHora++;
}
System.out.print(celda + ":");
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
double mediaSemanal = consumoTotalSemana / (double) DIAS;
System.out.printf("Media semanal: %.2f%n", mediaSemanal);
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
class SimulacionHotel {

    private static final int PLANTAS = 7;
    private static final int HABITACIONES = 6;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
if (hayRayo && columna == columnaRayo) {
    celda = SIMBOLO_RAYO;
} else if (hayMantenimiento && planta == plantaMantenimiento && hora >= horaMantenimiento) {
    celda = SIMBOLO_MANTENIMIENTO;
} else {
    boolean persianaAbierta = random.nextDouble() < PROB_PERSIANA;
    boolean luzEncendida = random.nextDouble() < PROB_LUZ;
    if (persianaAbierta && luzEncendida) {
        celda = SIMBOLO_PERSIANA_LUZ;
    } else if (persianaAbierta) {
        celda = SIMBOLO_PERSIANA;
    } else {
        celda = SIMBOLO_VACIO;
    }
}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/54b37c9b9f12ac5776649e3dd1cd8aa14198a8de/entregas/aresHector/Hotel.java) (Reto 003)

```java
if (hayRayo)
    System.out.println("Un rayo ha inutilizado la columna " + columnaRayo);
if (hayMantenimiento && hora == horaMantenimiento)
    System.out.println(plantaMantenimiento + "ª planta en mantenimiento");
```

¿Qué observas en este código?


