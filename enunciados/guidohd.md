# Examen Parcial - GuidoHD

**Usuario GitHub:** GuidoHD
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

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
final String TEJADO = "               __/\\__\n" +
                      "  |    |    |  |####|  |    |    |  \n" +
                      "====================================";
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
for (int dia = 1; dia <= DIAS; dia++) {
    for (int hora = 0; hora < HORAS_POR_DIA; hora++) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
String fila = ":";
int lado = HABITACIONES / 2;
// ...
fila += ESPACIO_CENTRAL + ":";
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
boolean persiana_abierta = Math.random() < PROBABILIDAD_PERSIANA_ABIERTA;
boolean luz_encendida = Math.random() < PROBABILIDAD_LUZ_ENCENDIDA;
if (persiana_abierta) {
    fila += PERSIANA_ABIERTA;
} else {
    fila += (luz_encendida ? LUZ_ENCENDIDA : LUZ_APAGADA);
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
System.out.println("Día " + dia + " - " + (hora < 10 ? "0" + hora : hora) + ":00h\n");
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
for (int numero_planta = PLANTAS; numero_planta >= 1; numero_planta--) {
    String fila = ":";
    int lado = HABITACIONES / 2;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
for (int i = 0; i < lado; i++) {
    boolean persiana_abierta = Math.random() < PROBABILIDAD_PERSIANA_ABIERTA;
    boolean luz_encendida = Math.random() < PROBABILIDAD_LUZ_ENCENDIDA;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
final String TEJADO = "               __/\\__\n" + "  |    |    |  |####|  |    |    |  \n" + "====================================";

final String SUELO = "------------------------------------\n" + "     ==========================\n" + "   ==============================\n" + " ==================================\n";
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1ce0c911d2fddb8930e1a76dea5c498a875b9fe8/entregas/marcos.huidobro/UnEdificio.java) (Reto 003)

```java
if (i < lado - 1) fila += ":";
```

¿Qué observas en este código?


