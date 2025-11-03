# Examen Parcial - fernandezviaderodavid-ui

**Usuario GitHub:** fernandezviaderodavid-ui
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

Archivo: `RetoEdificioBase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioBase.java) (Reto 003)

```java
for (int dia = 1; dia <= 7; dia++) {
    for (int hora = 1; hora <= 24; hora++) {
        System.out.println("Día " + dia + " - " + hora + ":00h");
        mostrarHotel(PLANTAS, HABITACIONES);
        System.out.println();
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `RetoEdificioBase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioBase.java) (Reto 003)

```java
double probPersianaAbierta = Math.random();
double probLuzEncendida = Math.random();
boolean persianaAbierta = probPersianaAbierta < 0.7;
boolean luzEncendida = probLuzEncendida < 0.6;
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `RetoEdificioBase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioBase.java) (Reto 003)

```java
if (persianaAbierta) {
    return "[ ]";
} else {
    if (luzEncendida) {
        return "[º]";
    } else {
        return "[*]";
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `RetoEdificioExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioExtendido.java) (Reto 003)

```java
int consumoSemanal = 0;
// ...
for (int dia = 1; dia <= DIAS_SEMANA; dia++) {
    int consumoDia = 0;
    for (int hora = 1; hora <= HORAS_DIA; hora++) {
        int consumoHora = mostrarHotelYContar(PLANTAS, HABITACIONES);
        consumoDia += consumoHora;
        System.out.println("Día " + dia + " - " + hora + ":00h  Consumo hora: " + consumoHora);
    }
    System.out.println("Consumo total del día " + dia + ": " + consumoDia);
    consumoSemanal += consumoDia;
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `RetoEdificioExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioExtendido.java) (Reto 003)

```java
for (int dia = 1; dia <= DIAS_SEMANA; dia++) {
    int consumoDiaSimulado = (int) (600 + Math.random() * 80);
    System.out.print("D" + dia + ": " + consumoDiaSimulado + " | ");
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `RetoEdificioExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioExtendido.java) (Reto 003)

```java
for (int dia = 1; dia <= DIAS_SEMANA; dia++) {
    int consumoDiaSimulado = (int) (600 + Math.random() * 80); // simulamos un valor cercano
    System.out.print("D" + dia + ": " + consumoDiaSimulado + " | ");
}
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `RetoEdificioBase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioBase.java) (Reto 003)

```java
static String generarVentana() {
    double probPersianaAbierta = Math.random(); // 0–1
    double probLuzEncendida = Math.random();

    boolean persianaAbierta = probPersianaAbierta < 0.7;
    boolean luzEncendida = probLuzEncendida < 0.6;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `RetoEdificioExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioExtendido.java) (Reto 003)

```java
if (luzEncendida) {
    lucesEncendidas++;
}

// mostramos el estado visual ASCII
if (persianaAbierta) {
    System.out.print("[ ]");
} else {
    if (luzEncendida) {
        System.out.print("[º]");
    } else {
        System.out.print("[*]");
    }
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `RetoEdificioExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9b3bf8d7c1f80b5b9fa735fa35d5cfa5abe171cb/entregas/Reto-003/RetoEdificioExtendido.java) (Reto 003)

```java
if (hab < habitaciones) System.out.print(":");
```

¿Qué observas en este código?


