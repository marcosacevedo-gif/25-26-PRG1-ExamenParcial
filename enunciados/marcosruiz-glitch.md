# Examen Parcial - marcosruiz-glitch

**Usuario GitHub:** marcosruiz-glitch
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 002

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

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9e22e6b4d9d17e163a7524e158e4c81911b2a8c4/batalla.java) (Reto 002)

```java
final int DAÑO_ESPADA = 2;
int vidaGuerrero = 20;
final double PORCENTAJE_EXITO_GUERRERO = 0.5;
// ...
final int MORDIDA = 4;
int vidaVampiro = 10;
final double PORCENTAJE_EXITO_VAMPIRO = 0.5;
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9e22e6b4d9d17e163a7524e158e4c81911b2a8c4/batalla.java) (Reto 002)

```java
if (Math.random() < PORCENTAJE_EXITO_GUERRERO) {
    vidaVampiro = vidaVampiro - DAÑO_ESPADA;
    System.out.println("¡El vampiro recibe la ostia!");
} else {
    System.out.println("¡El vampiro esquiva la ostia!");
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9e22e6b4d9d17e163a7524e158e4c81911b2a8c4/batalla.java) (Reto 002)

```java
boolean vampiroVivo = vidaVampiro > 0;
if (vampiroVivo) {
    if (Math.random() < PORCENTAJE_EXITO_VAMPIRO) {
        vidaGuerrero = vidaGuerrero - MORDIDA;
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9e22e6b4d9d17e163a7524e158e4c81911b2a8c4/batalla.java) (Reto 002)

```java
System.out.println("vidaGuerrero [" + vidaGuerrero + "] / vidaVampiro [" + vidaVampiro + "]");
boolean guerreroVivo = vidaGuerrero > 0;
algunMuerto = !guerreroVivo || !vampiroVivo;
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9e22e6b4d9d17e163a7524e158e4c81911b2a8c4/batalla.java) (Reto 002)

```java
String elGanador = vidaGuerrero > 0 ? "Guerrero" : "Vampiro";
System.out.println("Ganó el " + elGanador);
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Batalla.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Amarcosruiz-glitch+is%3Aall) (Reto 002)

```java
do {

    if (Math.random() < PORCENTAJE_EXITO_GUERRERO) {
        vidaVampiro = vidaVampiro - DAÑO_ESPADA;
        System.out.println("¡El vampiro recibe la ostia!");
    } else {
        System.out.println("¡El vampiro esquiva la ostia!");
    }

    boolean vampiroVivo = vidaVampiro > 0;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9e22e6b4d9d17e163a7524e158e4c81911b2a8c4/entregas/Edificio.java) (Reto 003)

```java
Boolean abierta, encendida;

for (int dia = 0; dia < 7; dia++) {
    for (int hora = 0; hora < 24; hora++) {
        System.out.println("son las " + hora + " del dia " + dia);
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/9e22e6b4d9d17e163a7524e158e4c81911b2a8c4/entregas/Edificio.java) (Reto 003)

```java
for (int columna = 1; columna <= 6; columna++) {
    if (columna == 3) {
        System.out.print(SEPARADOR);
    }

    abierta = Math.random() < PERSIANA_ABIERTA;
    encendida = Math.random() < LUZ_ENCENDIDA;
    System.out.print(!abierta ? VENTANA_CERRADA
            : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Batalla.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Amarcosruiz-glitch+is%3Aall) (Reto 002)

```java
boolean vampiroVivo = vidaVampiro > 0;

if (vampiroVivo) {
    if (Math.random() < PORCENTAJE_EXITO_VAMPIRO) {
        vidaGuerrero = vidaGuerrero - MORDIDA;
        System.out.println("¡El guerrero recibe la ostia!");
    } else {
        System.out.println("¡El guerrero esquiva la ostia!");
    }
}

System.out.println("vidaGuerrero [" + vidaGuerrero + "] / vidaVampiro [" + vidaVampiro + "]");

boolean guerreroVivo = vidaGuerrero > 0;

algunMuerto = !guerreroVivo || !vampiroVivo;
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `Batalla.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Amarcosruiz-glitch+is%3Aall) (Reto 002)

```java
boolean guerreroVivo = vidaGuerrero > 0;

algunMuerto = !guerreroVivo || !vampiroVivo;

} while (!algunMuerto);
```

¿Qué observas en este código?

