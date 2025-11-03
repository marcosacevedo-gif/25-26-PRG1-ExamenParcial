# Examen Parcial - Extra 04

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

Archivo: `Reto3.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3b54c071dd690f3d9fab8141edc9b686d7cd498d/entregas/AznarCarlos/reto-003/Reto3.java) (Reto 003, líneas 28-31)

```java
System.out.print(
        !abierta ? (encendida ? VENTANA_CERRADA : VENTANA_ABIERTA_CON_LUZ)
                : VENTANA_ABIERTA_SIN_LUZ);
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
for (int dia = 1; dia <= 7; dia++) {
    for (int hora = 0; hora < 24; hora++) {
        System.out.print("Son las " + hora + "del dia " + dia);
        System.out.println();
        System.out.println("               __/\\__\n" + //
                "  |    |    |  |####|  |    |    |  \n" + //
                "====================================");
        for (int planta = 1; planta <= 7; planta++) {
            for (int columna = 1; columna <= 6; columna++) {
```

¿Qué observas en este código?

---

## Pregunta 3

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

## Pregunta 4

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4d7909c8c0fd87d1f339f1f8445afe00b92ce200/entregas/bolivarMarcos/UnEdificio.java) (Reto 003)

```java
final String LADRILLOS = ":";
// ...
System.out.print(LADRILLOS + (!abierta ? VENTANA_CERRADA : encendida ? LUZ_ENCENDIDA : LUZ_APAGADA) + LADRILLOS);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/fc37f36790acb17b30da59944d74627149443ed5/entregas/raposoEdgar/edificio.java) (Reto 003)

```java
System.out.println("Dia " + dia + " - " + hora + ":00  Consumo hora: " + consumoDia);
```

¿Qué observas en este código?

