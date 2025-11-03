# Examen Parcial - adrianaaguilar-hub

**Usuario GitHub:** adrianaaguilar-hub
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002, Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 5 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `HeroeVsVampiroCompleto.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/cea77e114d2f9b9ba0f1a05dc17b598856bbc666/entregas/aguilarAdriana/retos/Reto002/HeroeVsVampiroCompleto.java) (Reto 002)

```java
if (ataqueElegidoCaballero == 1) {
    if (Math.random() <= PROB_ARMA_UNO_HEROE) {
        vidaVampiro = vidaVampiro - ARMA_UNO_HEROE;
        System.out.println("¡Tu Arma 1 golpea al vampiro! -" + ARMA_UNO_HEROE + " HP");
    } else {
        System.out.println("¡Tu Arma 1 falló!");
    }
}
if (ataqueElegidoCaballero == 2) { /* ... */ }
if (ataqueElegidoCaballero == 3) { /* ... */ }
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `HeroeVsVampiroCompleto.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/cea77e114d2f9b9ba0f1a05dc17b598856bbc666/entregas/aguilarAdriana/retos/Reto002/HeroeVsVampiroCompleto.java) (Reto 002)

```java
if (vidaVampiro > 0) {
    int ataqueAleatorio = (int)(Math.random()*3) + 1;
    if (ataqueAleatorio == 1) { /* ... */ }
    if (ataqueAleatorio == 2) { /* ... */ }
    if (ataqueAleatorio == 3) { /* ... */ }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `UnGuerrero.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/cea77e114d2f9b9ba0f1a05dc17b598856bbc666/entregas/aguilarAdriana/retos/Reto002/UnGuerrero.java) (Reto 002)

```java
int dañoGuerrero = 2;
System.out.println("¡El guerrero golpea!" + dañoGuerrero + " HP");
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2efe7a9bd6bf4b36835e954ae820ea7084a6f295/entregas/aguilarAdriana/retos/Reto003/Edificio.java) (Reto 003)

```java
for (int hora = 0; hora <= 24; hora++) {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/2efe7a9bd6bf4b36835e954ae820ea7084a6f295/entregas/aguilarAdriana/retos/Reto003/Edificio.java) (Reto 003)

```java
System.out.print(":" + (abierto ? (encendido ? "[*]" : "[º]") : "[ ]") + ":");
```

¿Qué observas en este código?

