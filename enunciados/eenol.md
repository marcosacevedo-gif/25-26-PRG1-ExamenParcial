# Examen Parcial - eenol

**Usuario GitHub:** eenol
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

Archivo: `SimulacionHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/61896085e1000d61811ce32fcf7eb625aa69f23f/entregas/hidalgoenol/SimulacionHotel.java) (Reto 003)

```java
class SimulacionHotel {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `SimulacionHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/61896085e1000d61811ce32fcf7eb625aa69f23f/entregas/hidalgoenol/SimulacionHotel.java) (Reto 003)

```java
while (dia <= DIAS) {
    int consumoDia = 0;
    // ...
    int hora = 0;
    while (hora < HORAS) {
        // ...
        hora++;
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `SimulacionHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/61896085e1000d61811ce32fcf7eb625aa69f23f/entregas/hidalgoenol/SimulacionHotel.java) (Reto 003)

```java
if (hayRayo && c == columnaRayo) {
    celda = "[X]";
} else if (hayMantenimiento && p == plantaMantenimiento && hora >= horaMantenimiento) {
    celda = "[#]";
} else if (persianaAbierta && luzEncendida) {
    celda = "[*]";
    consumoDia++;
} else if (persianaAbierta && !luzEncendida) {
    celda = "[º]";
} else {
    celda = "[ ]";
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `SimulacionHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/61896085e1000d61811ce32fcf7eb625aa69f23f/entregas/hidalgoenol/SimulacionHotel.java) (Reto 003)

```java
System.out.println("Dia " + dia + " - " + hora + ":00  Consumo hora: " + consumoDia);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `SimulacionHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/61896085e1000d61811ce32fcf7eb625aa69f23f/entregas/hidalgoenol/SimulacionHotel.java) (Reto 003)

```java
System.out.println("Media semanal: " + (consumoTotalSemana / 7));
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aeenol+is%3Aall) (Reto 003, línea 3)

```java
final String TECHO_DEL_EDIFICIO = "               __/\\__";
final String PARTE_DEABJO_DEL_TECHO = "  |    |    |  |####|  |    |    |  ";
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aeenol+is%3Aall) (Reto 003, línea 18)

```java
boolean luzEncencida, persianaAbierta;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aeenol+is%3Aall) (Reto 003, líneas 26-34)

```java
for (int planta = 1; planta <= PLANTA_MAXIMA; planta++) {
    for (int columna = 1; columna <= 6; columna++) {
        persianaAbierta = Math.random() < PROBABILIDAD_PERSIANA_ABIERTA;
        luzEncencida = Math.random() < PROBABILIDAD_LUZ_ENCENDIDA;

        System.out.print(
                !persianaAbierta ? VENTANA_CERRADA
                        : luzEncencida ? VENTANA_LUZ_ENCENDIDA : VENTANA_LUZ_APAGADA);
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aeenol+is%3Aall) (Reto 003, línea 37)

```java
System.out.print("- P" + (PLANTA_MAXIMA + 1 - planta));
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aeenol+is%3Aall) (Reto 003, línea 1)

```java
public class Edificio {
```

¿Qué observas en este código?

