# Examen Parcial - edgarraposo-glitch

**Usuario GitHub:** edgarraposo-glitch
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

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/fc37f36790acb17b30da59944d74627149443ed5/entregas/raposoEdgar/edificio.java) (Reto 003)

```java
class edificio {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/fc37f36790acb17b30da59944d74627149443ed5/entregas/raposoEdgar/edificio.java) (Reto 003)

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

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/fc37f36790acb17b30da59944d74627149443ed5/entregas/raposoEdgar/edificio.java) (Reto 003)

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

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/fc37f36790acb17b30da59944d74627149443ed5/entregas/raposoEdgar/edificio.java) (Reto 003)

```java
System.out.println("Dia " + dia + " - " + hora + ":00  Consumo hora: " + consumoDia);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/fc37f36790acb17b30da59944d74627149443ed5/entregas/raposoEdgar/edificio.java) (Reto 003)

```java
System.out.println("Media semanal: " + (consumoTotalSemana / 7));
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aedgarraposo-glitch+is%3Aall) (Reto 003, líneas 5-6)

```java
int PERSIANA_ABIERTA = 0.7;
int LUZ_ENCENDIDA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aedgarraposo-glitch+is%3Aall) (Reto 003, línea 17)

```java
for (int planta = 1; planta <= 6; planta++) {
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aedgarraposo-glitch+is%3Aall) (Reto 003, línea 21)

```java
System.out.println(!abierta ? VENTANA_CERRADA : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Edificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Aedgarraposo-glitch+is%3Aall) (Reto 003, línea 2)

```java
class Edificio {
```

¿Qué observas en este código?

