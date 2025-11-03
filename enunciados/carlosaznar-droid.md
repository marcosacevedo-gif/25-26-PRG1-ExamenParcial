# Examen Parcial - carlosaznar-droid

**Usuario GitHub:** carlosaznar-droid
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

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003)

```java
final String SEPARADOR = "[   ]";
final String TECHO = "||   |   |###|   |   ||";
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003)

```java
for (int hora = 0; hora < 24; hora++) {
    System.out.println("Son las " + hora + ":00 del día " + dia);
    for (int i = 0; i < 1; i++) {
        System.out.println(TECHO);
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003)

```java
System.out.print(
    !abierta ? (encendida ? VENTANA_CERRADA : VENTANA_ABIERTA_CON_LUZ)
             : VENTANA_ABIERTA_SIN_LUZ);
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003)

```java
for (int planta = 1; planta <= 7; planta++) {
    for (int columna = 1; columna <= 6; columna++) {
        // ...
        if (columna == 3) {
            System.out.print(SEPARADOR);
        }
    }
    System.out.println();
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003)

```java
public class Reto3{
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003, líneas 28-31)

```java
System.out.print(
        !abierta ? (encendida ? VENTANA_CERRADA : VENTANA_ABIERTA_CON_LUZ)
                : VENTANA_ABIERTA_SIN_LUZ);
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003, líneas 18-22)

```java
for (int i = 0; i < 1; i++) {
    System.out.println(TECHO);

}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003, líneas 5-7)

```java
final double PERSIANA_ABIERTA = 0.7;
final double LUZ_ENCENDIDA = 0.6;
```

¿Qué observas en este código?


