# Examen Parcial - Guillermo-Castaneda

**Usuario GitHub:** Guillermo-Castaneda
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

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
final int PLANTAS = 8;
String[][] edificio = new String[7][HABITACIONES];
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
String ABIERTA = "[ ]";
String CERRADA_APAGADA = "[º]";
String CERRADA_ENCENDIDA = "[*]";
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
if (Math.random() < PROB_MANTENIMIENTO) {
    plantaMantenimiento = (int) (Math.random() * 7);
}
// ...
if (!rayoCaido && Math.random() < PROB_RAYO) {
    columnaAveriada = (int) (Math.random() * HABITACIONES);
    rayoCaido = true;
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
for (int i = 6; i >= 0; i--) {
    System.out.print(":");
    for (int j = 0; j < HABITACIONES; j++) {
        if (j == 3) System.out.print(ESPACIO);
        System.out.print(edificio[i][j] + ":");
    }
    System.out.println(" - P" + (i + 1));
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
System.out.println("Día " + dia + " - " + hora + ":00h  Consumo hora: " + consumoHora);
// ...
System.out.println("Media de consumo semanal: " + media);
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
String ABIERTA = "[ ]";
String CERRADA_APAGADA = "[º]";
String CERRADA_ENCENDIDA = "[*]";
String AVERIA = "[X]";
String MANTENIMIENTO = "[#]";
String ESPACIO = ":[    ]:";
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
System.out.println("Simulación del hotel en la esquina de Agonía con Mortificación");
System.out.println("Ventana cerrada - Luz apagada - Luz encendida - Avería - Mantenimiento");
System.out.println("[ ] - [º] - [*] - [X] -[#]");
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
System.out.println("               __/\__");
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
if (columnaAveriada != -1 && hora == 8) {
    System.out.println(" Un rayo ha inutilizado la columna " + (columnaAveriada + 1));
}
if (plantaMantenimiento != -1 && hora == 8) {
    System.out.println(" Planta " + (plantaMantenimiento + 1) + " en mantenimiento");
}
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
for (int j = 0; j < HABITACIONES; j++) {
    if (i == plantaMantenimiento) {
        edificio[i][j] = MANTENIMIENTO;
    } else if (j == columnaAveriada) {
        edificio[i][j] = AVERIA;
    } else {
```

¿Qué observas en este código?


