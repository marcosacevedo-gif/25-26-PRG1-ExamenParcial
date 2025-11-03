# Examen Parcial - JavierQuisphe

**Usuario GitHub:** JavierQuisphe
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 003

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

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
for (int dia = 1; dia <= TOTAL_DIAS; dia++) {
    for (int hora = 0; hora < HORAS_POR_DIA; hora++) {
        System.out.println("Dia " + dia + " - " + hora + ":00h");
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
System.out.println("Ventana cerrada\tLuz apagada\tLuz encendida");
System.out.println("[ ]\t[º]\t[*]");
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
boolean persianaAbierta = random.nextDouble() < PROBABILIDAD_PERSIANA_ABIERTA;
if (persianaAbierta) {
    boolean luzEncendida = random.nextDouble() < PROBABILIDAD_LUZ_ENCENDIDA;
    System.out.print(luzEncendida ? "[*]" : "[º]");
} else {
    System.out.print("[ ]");
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
if (habitacion == HABITACION_ASCENSOR) {
    System.out.print("[    ]");
}
// ...
if (habitacion != HABITACIONES_POR_PLANTA) {
    System.out.print("::");
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
System.out.println(" ==================================");
System.out.println();
System.out.println();
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
private static final int TOTAL_DIAS = 7;
private static final int HORAS_POR_DIA = 24;
private static final int TOTAL_PLANTAS = 7;
private static final int HABITACIONES_POR_PLANTA = 6;
private static final int HABITACION_ASCENSOR = 4;
private static final double PROBABILIDAD_PERSIANA_ABIERTA = 0.7;
private static final double PROBABILIDAD_LUZ_ENCENDIDA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
System.out.println("Dia " + dia + " - " + hora + ":00h");
System.out.println("Ventana cerrada\tLuz apagada\tLuz encendida");
System.out.println("[ ]\t[º]\t[*]");
System.out.println();
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
if (habitacion == HABITACION_ASCENSOR) {
    System.out.print("[    ]");
} else {
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
boolean persianaAbierta = random.nextDouble() < PROBABILIDAD_PERSIANA_ABIERTA;

if (persianaAbierta) {
    boolean luzEncendida = random.nextDouble() < PROBABILIDAD_LUZ_ENCENDIDA;

    if (luzEncendida) {
        System.out.print("[*]");
    } else {
        System.out.print("[º]");
    }
} else {
    System.out.print("[ ]");
}
```

¿Qué observas en este código?


