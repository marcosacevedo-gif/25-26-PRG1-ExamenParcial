# Examen Parcial - miguelgomz

**Usuario GitHub:** miguelgomz
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

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/123ede67dbc64212199fb561a9e028c8efc4d657/entregas/gomezmiguel/src/Hotel.java) (Reto 003)

```java
for (int hora = 0; hora < 24; hora++) {
    int consumoHora = 0;
    boolean rayoHora = !rayoDia && random.nextDouble() < 0.2;
    if (rayoHora) { rayoDia = true; columnaRayo = random.nextInt(6) + 1; }
    // ... impresión de hotel y consumo
}
```

¿Qué observas en este código?

---

## Pregunta 2

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

## Pregunta 3

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/123ede67dbc64212199fb561a9e028c8efc4d657/entregas/gomezmiguel/src/Hotel.java) (Reto 003)

```java
if (mantenimientoDia && planta == plantaMantenimiento) {
    estado = MANTENIMIENTO;
} else if (rayoDia && habitacion == columnaRayo) {
    estado = AVERIADA;
} else {
    boolean persianaAbierta = random.nextDouble() < 0.7;
    boolean luzEncendida = random.nextDouble() < 0.6;
    if (persianaAbierta) {
        estado = luzEncendida ? LUZ_ENCENDIDA : LUZ_APAGADA;
    } else {
        estado = VENTANA_CERRADA;
        if (luzEncendida) {
            consumoHora++;
        }
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/123ede67dbc64212199fb561a9e028c8efc4d657/entregas/gomezmiguel/src/Hotel.java) (Reto 003)

```java
StringBuilder consumosStr = new StringBuilder("CONSUMOS:");
for (int d = 1; d <= dia; d++) {
    consumosStr.append(" D").append(d).append(": ").append(consumosDiarios[d - 1]);
    if (d < dia) { consumosStr.append(" |"); }
}
System.out.println(consumosStr.toString());
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/123ede67dbc64212199fb561a9e028c8efc4d657/entregas/gomezmiguel/src/Hotel.java) (Reto 003)

```java
System.out.println("Media de consumo semanal: " + (totalConsumoSemanal / 7));
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Vampiros.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/b0a8a82c5b897d0c4ff518e6e9163cbef9dff122/entregas/gomezmiguel/src/Vampiros.java) (Reto 002)

```java
import java.util.Scanner

public class Vampiros {
    private static final int VIDA_INICIAL_HEROE = 150;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Vampiros.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/b0a8a82c5b897d0c4ff518e6e9163cbef9dff122/entregas/gomezmiguel/src/Vampiros.java) (Reto 002)

```java
private static int procesarAtaqueHeroe(int opcion, int vidaVampiro) {
    // ... código ...
    if (Math.random() < prob) {
        if (esDefensa) {
            System.out.println("Te defiendes exitosamente del vampiro.");
            return REDUCCION_DEFENSA;
        } else {
            System.out.println("El vampiro recibe un tajo!!");
            vidaVampiro -= danio;
        }
    }
    // ...
    return 0;
}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Vampiros.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/b0a8a82c5b897d0c4ff518e6e9163cbef9dff122/entregas/gomezmiguel/src/Vampiros.java) (Reto 002)

```java
private static void procesarAtaqueVampiro(int vidaHeroe) {
    // ... código ...
    if (Math.random() < prob) {
        System.out.println("El héroe recibe un mordisco!!");
        vidaHeroe -= danio;
    } else {
        System.out.println("El héroe esquiva el mordisco.");
    }
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Hotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/123ede67dbc64212199fb561a9e028c8efc4d657/entregas/gomezmiguel/src/Hotel.java) (Reto 003)

```java
for (int habitacion = 1; habitacion <= 7; habitacion++) {
    if (habitacion == 4) {
        System.out.print(PASILLO);
        continue;
    }
    String estado;
    if (mantenimientoDia && planta == plantaMantenimiento) {
        estado = MANTENIMIENTO;
    } else if (rayoDia && habitacion == columnaRayo) {
        estado = AVERIADA;
    } else {
        boolean persianaAbierta = random.nextDouble() < 0.7;
        boolean luzEncendida = random.nextDouble() < 0.6;
        if (persianaAbierta) {
            estado = luzEncendida ? LUZ_ENCENDIDA : LUZ_APAGADA;
        } else {
            estado = VENTANA_CERRADA;
            if (luzEncendida) {
                consumoHora++;
            }
        }
    }
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `ConversorSegundos` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/debe66a1a5b8e1b08d18a29c008d41958c1c4723/entregas/gomezmiguel/ConversorSegundos) (Reto 001)

```java
if (dias > 0) {
    String unidadDias = dias == 1 ? "día" : "días";
    System.out.println(dias + " " + unidadDias);
}
if (horas > 0) {
    String unidadHoras = horas == 1 ? "hora" : "horas";
    System.out.println(horas + " " + unidadHoras);
}
if (minutos > 0) {
    String unidadMinutos = minutos == 1 ? "minuto" : "minutos";
    System.out.println(minutos + " " + unidadMinutos);
}
```

¿Qué observas en este código?


