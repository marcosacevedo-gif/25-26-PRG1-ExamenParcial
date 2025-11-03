# Examen Parcial - Extra 01

**Fecha:** 4 de noviembre de 2025

---

## Instrucciones

A continuación encontrarás 5 fragmentos de código extraídos de exámenes reales de tus compañeros.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 5 preguntas (elige libremente).


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

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
for (int planta = 1; planta <= NUMERO_DE_PLANTAS; planta++) {
    for (int ventana = 1; ventana <= NUMERO_DE_VENTANAS; ventana++) {

        abierta = Math.random() < PERSIANA_ABIERTA;
        encendida = Math.random() < LUZ_ENCENDIDA;
        System.out.print(!abierta ? VENTANA_CERRADA
                : encendida ? VENTANA_ABIERTA_LUZ_ENCENDIDA : VENTANA_ABIERTA_LUZ_APAGADA);
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `SimulacionDeHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotel.java) (Reto 003)

```java
for(int hora=0;hora<=24;hora++) {
    // ...
    System.out.println("Día " + dia + ", Hora " + hora + ":00h");
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/reto-003/Edificio.java) (Reto 003)

```java
class Edificio {

    public static void main(String[] args) {

    }

    final double PERSIANA_ABIERTA = 0.7;
    final double LUZ_ENCENDIDA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `CalculadoraCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/CalculadoraCambio.java) (Reto 001)

```java
int resto = vuelta % 100;
int cociente = vuelta / 100;
System.out.println(cociente + " billete(s) de 100 euros");
// ... (se reusa cociente/resto)
System.out.println(resto + " moneda(s) de 1 euros");
```

¿Qué observas en este código?

