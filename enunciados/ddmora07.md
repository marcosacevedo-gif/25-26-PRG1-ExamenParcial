# Examen Parcial - ddmora07

**Usuario GitHub:** ddmora07
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

Archivo: `Edificiointereactivo.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/166e129d4c0c4cf46f752f8011ed5a2626eb42ec/entregas/moraDaniel/Edificiointereactivo.java) (Reto 003)

```java
class Edificiointereactivo {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Edificiointereactivo.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/166e129d4c0c4cf46f752f8011ed5a2626eb42ec/entregas/moraDaniel/Edificiointereactivo.java) (Reto 003)

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

Archivo: `Edificiointereactivo.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/166e129d4c0c4cf46f752f8011ed5a2626eb42ec/entregas/moraDaniel/Edificiointereactivo.java) (Reto 003)

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

Archivo: `Edificiointereactivo.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/166e129d4c0c4cf46f752f8011ed5a2626eb42ec/entregas/moraDaniel/Edificiointereactivo.java) (Reto 003)

```java
System.out.println("Dia " + dia + " - " + hora + ":00  Consumo hora: " + consumoDia);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificiointereactivo.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/166e129d4c0c4cf46f752f8011ed5a2626eb42ec/entregas/moraDaniel/Edificiointereactivo.java) (Reto 003)

```java
System.out.println("Media semanal: " + (consumoTotalSemana / 7));
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `UnEdificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Addmora07+is%3Aall) (Reto 003, línea 10)

```java
final String LADRILLOS = ":";
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `UnEdificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Addmora07+is%3Aall) (Reto 003, líneas 15-16)

```java
int numeroEncendidas=0;
int totalGastodia=0;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `UnEdificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Addmora07+is%3Aall) (Reto 003, líneas 27-40)

```java
for (int columna = 1; columna <= 7; columna++) {
    for (int fila = 1; fila <= 7; fila++) {

        abierta = Math.random() < PROBABILIDAD_PERSIANA_ABIERTA;
        encendida = Math.random() < PROBABILIDAD_LUZ_ENCENDIDA;
        if (fila == 4) {
            System.out.print(ASCENSOR);
        } else {
            System.out.print(
                    LADRILLOS + (!abierta ? VENTANA_CERRADA : encendida ? LUZ_ENCENDIDA : LUZ_APAGADA)
                            + LADRILLOS);
            if(abierta && encendida){
                numeroEncendidas++;
                totalGastodia++;
            }
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `UnEdificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Addmora07+is%3Aall) (Reto 003, línea 30)

```java
abierta = Math.random() < PROBABILIDAD_PERSIANA_ABIERTA;
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `UnEdificio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Addmora07+is%3Aall) (Reto 003, línea 4)

```java
public class UnEdificio {
```

¿Qué observas en este código?

