# Examen Parcial - Extra 02

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

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003)

```java
for (int planta=1 ; planta <=7; planta++) {
  for (int columna=1 ; columna <=6; columna++) {
      abierta =Math.random() < PERSIANA_ABIERTA;
      encendida =Math.random() < LUZ_ENCENDIDA;
      System.out.println(!abierta ? VENTANA_CERRADA: (encendida ? VENTANA_ABIERTA_CON_LUZ: VENATANA_ABIERTA_SIN_LUZ));
  }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
public class HotelDeLaAgonia {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `HotelLuces.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/0940bca38a3852dfc71939340aea56c2d6eddd4b/entregas/arroyosanchezdaniel/HotelLuces.java) (Reto 003)

```java
if (probVentanaAbierta >= 0.7) {
    if (numeroHabitaciones != 4) {
        System.out.print(VENTANA_CERRADA);
    }
} else if (probVentanaAbierta < 0.7 && probLuzEncendida >= 0.6) {
    if (numeroHabitaciones != 4) {
        System.out.print(LUZ_APAGADA);
    }
} else if (probVentanaAbierta < 0.7 && probLuzEncendida < 0.6) {
    if (numeroHabitaciones != 4) {
        System.out.print(LUZ_ENCENDIDA);
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `RetoEdificioBase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5775efe8e9a4ee060cbcd6372a5e10ffabe22ba1/entregas/Reto-003/RetoEdificioBase.java) (Reto 003)

```java
try {
    Thread.sleep(300); // Pausa para ver el cambio (opcional)
} catch (InterruptedException e) {
    e.printStackTrace();
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/db74bf694d2a3fc707a9a6294d833d20a47131e1/entregas/Casta%C3%B1eda.Guillermo/Reto003.java) (Reto 003)

```java
String ABIERTA = "[ ]";
String CERRADA_APAGADA = "[º]";
String CERRADA_ENCENDIDA = "[*]";
```

¿Qué observas en este código?

