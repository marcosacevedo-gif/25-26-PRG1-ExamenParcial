# Examen Parcial - Extra 10

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

Archivo: `EdificioEnLaSemana.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ec637ba447a91c88c6b9ef4161a464cbc2d26250/entregas/melgaresjose/src/retoBase/EdificioEnLaSemana.java) (Reto 003)

```java
final int PLANTAS_HABITACIONES = 7;
final int HABITACIONES_POR_PLANTA = 6;
// ...
for(int planta = PLANTAS_HABITACIONES; planta>= 1; planta-- ){
    for(int habitacion = 1; habitacion <= HABITACIONES_POR_PLANTA; habitacion++) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

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

## Pregunta 3

Archivo: `Reto_002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/Reto_002.java) (Reto 002, líneas 23-27)

```java
boolean algunMuerto = false;
boolean guerreroVivo = true;
boolean vampiroVivo = true;
```

¿Qué observas en este código?

---

## Pregunta 4

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

---

## Pregunta 5

Archivo: `EdificioHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4f009518d4c48160b18f34b90c073e15ee126fbd/entregas/javierQuisphe/src/EdificioHotel.java) (Reto 003)

```java
System.out.println("Ventana cerrada\tLuz apagada\tLuz encendida");
System.out.println("[ ]\t[º]\t[*]");
```

¿Qué observas en este código?

