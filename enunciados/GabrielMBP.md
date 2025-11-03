# Examen Parcial - GabrielMBP

**Usuario GitHub:** GabrielMBP
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 7 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12dc820d49fab9feaab0d46987da27bf2236b0d1/entregas/bejarGabriel/reto003/Edificio.java) (Reto 003)

```java
int PERSIANA_ABIERTA = 0.7;
int LUZ_ENCENDIDA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12dc820d49fab9feaab0d46987da27bf2236b0d1/entregas/bejarGabriel/reto003/Edificio.java) (Reto 003)

```java
for (int planta = 1; planta <= 6; planta++) {
    for (int columna = 1; columna <= 6; columna++) {
        abierta = Math.random() < PERSIANA_ABIERTA;
        encendida = Math.random() < LUZ_ENCENDIDA;
        System.out.println(!abierta ? VENTANA_CERRADA : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
        if (columna == 3) {
            System.out.print(SEPARADOR);
        }
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12dc820d49fab9feaab0d46987da27bf2236b0d1/entregas/bejarGabriel/reto003/Edificio.java) (Reto 003)

```java
for (int dia = 1; dia <= 7; dia++) {
    for (int hora = 0; hora < 24; hora++) {
        System.out.println("Hora " + hora + " del día " + dia);
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12dc820d49fab9feaab0d46987da27bf2236b0d1/entregas/bejarGabriel/reto003/Edificio.java) (Reto 003)

```java
final String SEPARADOR = "[    ]";
// ... uso para la columna central
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12dc820d49fab9feaab0d46987da27bf2236b0d1/entregas/bejarGabriel/reto003/Edificio.java) (Reto 003)

```java
class Edificio {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12dc820d49fab9feaab0d46987da27bf2236b0d1/entregas/bejarGabriel/reto003/Edificio.java) (Reto 003)

```java
boolean abierta, encendida;

for (int dia = 1; dia <= 7; dia++) {
    for (int hora = 0; hora < 24; hora++) {
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/12dc820d49fab9feaab0d46987da27bf2236b0d1/entregas/bejarGabriel/reto003/Edificio.java) (Reto 003)

```java
for (int columna = 1; columna <= 6; columna++) {
    abierta = Math.random() < PERSIANA_ABIERTA;
    encendida = Math.random() < LUZ_ENCENDIDA;
    System.out.println(!abierta ? VENTANA_CERRADA : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
    if (columna == 3) {
        System.out.print(SEPARADOR);
    }
}
```

¿Qué observas en este código?


