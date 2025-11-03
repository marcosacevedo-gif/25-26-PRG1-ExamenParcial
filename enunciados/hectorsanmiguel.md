# Examen Parcial - hectorsanmiguel

**Usuario GitHub:** hectorsanmiguel
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 8 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
final String VENTANA_CERRADA = ":[ ]:";
final String VENTANA_ABIERTA_LUZ_APAGADA = ":[º]:";
final String VENTANA_ABIERTA_LUZ_ENCENDIDA = ":[*]:";
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

## Pregunta 3

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
for (int dia = 1; dia <= 7; dia++) {
    for (int hora = 0; hora < 24; hora++) {
        // ...
        System.out.println("Son las " + hora + ":00 del día " + dia);
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
final String SEPARADOR = ":[   ]:";
// ... uso con if (ventana == 3)
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
public class DibujadorDeEdificio {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
final String TECHO_EDIFICIO_ARRIBA = "               __/\\__";
final String TECHO_EDIFICIO_MEDIO = "  |    |    |  |####|  |    |    |  ";
final String TECHO_EDIFICIO_ABAJO = "====================================";
final String BASE_EDIFICIO = "------------------------------------";
final String PRIMER_SEPARADOR_ENTRE_EDIFICIOS = "     ==========================";
final String SEGUNDO_SEPARADOR_ENTRE_EDIFICIOS = "   ==============================";
final String TERCER_SEPARADOR_ENTRE_EDIFICIOS = " ==================================";
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `DibujadorDeEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4fb82157b5760bf9f83ccadef799ba24adf4cdc2/entregas/sanmiguelHector/reto-003/DibujadorDeEdificio.java) (Reto 003)

```java
final double PERSIANA_ABIERTA = 0.7;
final double LUZ_ENCENDIDA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 8

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


