# Examen Parcial - alejandrogomez3

**Usuario GitHub:** alejandrogomez3
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002, Reto 003

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

Archivo: `Reto003EdificioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12c10998a8134110cc74b49576117ea2cc5846ba/entregas/masiasManuel/src/Reto003EdificioFinal.java) (Reto 003)

```java
if (d == 1) fila.append("[9]:"); // Ascensor central
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Reto003EdificioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12c10998a8134110cc74b49576117ea2cc5846ba/entregas/masiasManuel/src/Reto003EdificioFinal.java) (Reto 003)

```java
System.out.println(" ==================================\n");
System.out.printf("Dia %d - %02d:00h Consumo hora: %d\n\n", dia + 1, hora, consumoHora);
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `ConversorDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/ConversorDuracion.java) (Ejercicios)

```java
int dias = segundosTotales / 86400;
segundosTotales %= 86400;
int horas = segundosTotales / 3600;
segundosTotales %= 3600;
int minutos = segundosTotales / 60;
int segundos = segundosTotales % 60;
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `DevolverCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/DevolverCambio.java) (Ejercicios)

```java
if (entregado < importe) {
    System.out.println("El dinero entregado debe ser mayor que el importe a pagar.");
    return;
}
// ...
Scanner scanner = new Scanner(System.in);
// ...
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `UnGuerrero.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/UnGuerrero.java) (Ejercicios)

```java
int dañoGuerrero = 2;
// ...
int dañoVampiro = 4;
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `UnGuerrero.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/UnGuerrero.java) (Reto 002, líneas 3-4)

```java
int vidaGuerrero = 20;
int dañoGuerrero = 2;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `UnGuerrero.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/UnGuerrero.java) (Reto 002, línea 16)

```java
final double PROBABILIDAD_DE_ATAQUE = 0.5;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `UnGuerrero.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/UnGuerrero.java) (Reto 002, línea 19)

```java
System.out.println("¡El guerrero golpea!" + dañoGuerrero + " HP");
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `UnGuerrero2.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/UnGuerrero2.java) (Reto 002, líneas 43-45)

```java
} else {
    System.out.println("Opción inválida. Pierdes el turno.");
    probabilidadHeroe = 0;
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `UnGuerrero2.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ae507fa3c77a26023f3e1c4a9f7a0aa13c563d32/entregas/UnGuerrero2.java) (Reto 002, línea 79)

```java
probabilidadVampiro = 0.30;
```

¿Qué observas en este código?

