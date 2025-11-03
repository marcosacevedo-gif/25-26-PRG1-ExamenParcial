# Examen Parcial - nicolascrespo-dotcom

**Usuario GitHub:** nicolascrespo-dotcom
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

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
for (int hora = 0; hora < 24; hora++) {
    System.out.print("Son las " + hora + "del dia " + dia);
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
if (columna == 3) {
    System.out.print(SEPARADOR);
} else {
    System.out.print(LADRILLOS + (!abierta ? VENTANA_CERRADA : (encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ)) + LADRILLOS);
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
final String VENTANA_ABIERTA_SIN_LUZ = "[º]";
final String VENTANA_ABIERTA_CON_LUZ = "[*]";
final String SEPARADOR = "[   ]";
final String LADRILLOS = ":";
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
System.out.println("               __/\\__\n" +
                  "  |    |    |  |####|  |    |    |  \n" +
                  "====================================");
// ...
System.out.println("------------------------------------\n" +
                   "     ==========================\n" +
                   "   ==============================\n" +
                   " ==================================");
```

¿Qué observas en este código?

---

## Pregunta 5

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

## Pregunta 6

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

## Pregunta 7

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
for (int columna = 1; columna <= 6; columna++) {
    abierta = Math.random() < PERSIANA_ABIERTA;
    encendida = Math.random() < LUZ_ENCENDIDA;
    if (columna == 3) {
        System.out.print(SEPARADOR);
    }else {System.out.print(LADRILLOS+(!abierta ? VENTANA_CERRADA: (encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ))+LADRILLOS);}
}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `batalla` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/319e41ca940d686ce0fc460f8ff2d4117acf3e53/batalla) (Reto 002)

```java
if (Math.random() < posibilidadExitoGuerrero && numeroArmaEscogida != 4) {
    System.out.println("El vampiro se lleva un golpe");
    vidaVampiro = vidaVampiro - dañoGuerrero;
} else if (Math.random() < posibilidadExitoGuerrero && numeroArmaEscogida == 4) {
    System.out.println("Te defiendes exitosamente del vampiro!!");
} else if (Math.random() > posibilidadExitoGuerrero && numeroArmaEscogida == 4) {
    System.out.println("No logras defenderte del vampiro!!");
} else {
    System.out.println("El vampiro ha esquivado el golpe");
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `batalla` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/319e41ca940d686ce0fc460f8ff2d4117acf3e53/batalla) (Reto 002)

```java
} else {
    System.out.println("Troleas y el vampiro se pica");
    posibilidadExitoGuerrero = 0;
    dañoGuerrero = 0;
    dañoVampiro = vidaGuerrero;
    probabilidadExitoVampiro = 1;
}
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `reto-003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2a6e8b6dfca704a09231d5ccc0d8dec2d30f3111/entregas/CrespoNicolas/reto-003.java) (Reto 003)

```java
        }
    }
}System.out.println("------------------------------------\n" + //
                                        "     ==========================\n" + //
                                        "   ==============================\n" + //
                                        " ==================================");
```

¿Qué observas en este código?


