# Examen Parcial - Extra 08

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

## Pregunta 2

Archivo: `SimulacionHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/68c3a571aa52659f92d22b863c17d3b5cd9f3ed9/entregas/yago.lopez/SimulacionHotel.java) (Reto 003)

```java
if (hayMantenimiento && hora == horaMantenimiento)
    System.out.println(plantaMantenimiento + "ª planta en mantenimiento");
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
for (int planta = 1; planta <= NUMERO_DE_PLANTAS; planta++) {
    for (int ventana = 1; ventana <= NUMERO_DE_VENTANAS; ventana++) {
        abierta = Math.random() < PERSIANA_ABIERTA;
        encendida = Math.random() < LUZ_ENCENDIDA;
        System.out.print(!abierta ? VENTANA_CERRADA
                : encendida ? VENTANA_ABIERTA_LUZ_ENCENDIDA : VENTANA_ABIERTA_LUZ_APAGADA);
        if (ventana == 3) {
            System.out.print(SEPARADOR);
        }
    }
    System.out.print("---P" + (NUMERO_DE_PLANTAS + 1 - planta));
    System.out.println();
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/123ede67dbc64212199fb561a9e028c8efc4d657/entregas/gomezmiguel/src/Hotel.java) (Reto 003)

```java
for (int planta = 7; planta >= 1; planta--) {
    for (int habitacion = 1; habitacion <= 7; habitacion++) {
        if (habitacion == 4) { System.out.print(PASILLO); continue; }
        String estado;
        // ... seleccion de estado
        System.out.print(":" + estado + ":");
    }
    System.out.print(SEPARADOR + "P" + planta);
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a57f109ee798efd2f5a3e197f889465a3e4cbe28/entregas/gonzalesDiego/src/Edificio.java) (Reto 003)

```java
final String VENTANA_CERRADA = ":[ ]:";
final String VENTANA_ABIERTA_CON_LUZ = ":[*]:";
final String VENTANA_ABIERTA_SIN_LUZ = ":[º]:";
```

¿Qué observas en este código?

