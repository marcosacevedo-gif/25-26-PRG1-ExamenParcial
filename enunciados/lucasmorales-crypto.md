# Examen Parcial - lucasmorales-crypto

**Usuario GitHub:** lucasmorales-crypto
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002, Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 7 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `CalcularPrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/d83296a923aa5942aec2d22be8940360c1919d51/entregas/MoralesLucas/reto-001/CalcularPrecioFinal.java) (Reto 001)

```java
double descuento = 0;
if (cantidad >= 10) descuento = 5;
if (cantidad >= 50) descuento = 10;
if (cantidad >= 100) descuento = 15;
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `ConvertirDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/d83296a923aa5942aec2d22be8940360c1919d51/entregas/MoralesLucas/reto-001/ConvertirDuracion.java) (Reto 001)

```java
int dias = s / 86400; s %= 86400;
int horas = s / 3600; s %= 3600;
int minutos = s / 60;
int segundos = s % 60;
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `DevolverCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/d83296a923aa5942aec2d22be8940360c1919d51/entregas/MoralesLucas/reto-001/DevolverCambio.java) (Reto 001)

```java
int cambio = paga - pagar;
// ...
int monedas1 = cambio / 1;
cambio = cambio % 1;
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `BatallaHeroeVampirobase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/d83296a923aa5942aec2d22be8940360c1919d51/entregas/MoralesLucas/reto-002/BatallaHeroeVampirobase.java) (Reto 002)

```java
while (hpGuerrero > 0 && hpVampiro > 0) {
    // ...
    if (hpVampiro <= 0) break;
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/d83296a923aa5942aec2d22be8940360c1919d51/entregas/MoralesLucas/reto-003/Edificio.java) (Reto 003)

```java
System.err.println(TECHO_ESPACIO_ABAJO);
for(int hora=0; hora<=24; hora++) {
    System.out.println("Son las " + hora + " horas"+" del día " + dia);
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `BatallaHeroeVampiro.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/d83296a923aa5942aec2d22be8940360c1919d51/entregas/MoralesLucas/reto-002/BatallaHeroeVampiro.java) (Reto 002)

```java
if (opcion == 1) {
    ataqueHeroe = 7;
    probExitoHeroe = 0.5;
} else if (opcion == 2) {
    ataqueHeroe = 15;
    probExitoHeroe = 0.25;
} else if (opcion == 3) {
    ataqueHeroe = 30;
    probExitoHeroe = 0.12;
} else {
    System.out.println("Opción no válida. Pierdes el turno.");
}
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `BatallaHeroeVampirobase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/d83296a923aa5942aec2d22be8940360c1919d51/entregas/MoralesLucas/reto-002/BatallaHeroeVampirobase.java) (Reto 002)

```java
if (random.nextDouble() < 0.5) {
    hpVampiro -= ataqueGuerrero;
    System.out.println("El guerrero golpea al vampiro con su hacha (-" + ataqueGuerrero + " HP)");
} else {
    System.out.println("El guerrero falla su ataque...");
}
```

¿Qué observas en este código?


