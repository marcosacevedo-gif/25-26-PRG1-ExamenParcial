# Examen Parcial - albertomeriino

**Usuario GitHub:** albertomeriino
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002

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

Archivo: `MinijuegoPelea.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto002/MinijuegoPelea.java) (Reto 002)

```java
double probabilidadGolpe = 0;
// ...
do {
    // lógica del turno
} while (!algunMuerto);
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `MinijuegoPelea.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto002/MinijuegoPelea.java) (Reto 002)

```java
final int DAÑO_ESPADA = 2;
final int DAÑO_MORDIDA = 4;
String Ganador = vidaGuerrero > 0 ? "El guerrero epico ha ganado la pelea." : "El sucio vampiro ha ganado la pelea.";
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `CalculadoraDeCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto001/CalculadoraDeCambio.java) (Reto 001)

```java
int billetes200 = dineroDevuelto / 200;
// ...
int billetes100 = dineroDevuelto / 100;
// ...
int billetes50 = dineroDevuelto / 50;
// ...
int monedas1 = dineroDevuelto / 1;
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `CalculadoraDeCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto001/CalculadoraDeCambio.java) (Reto 001)

```java
System.out.println("Cantidad de dinero a pagar: ");
int dineroPorPagar = scanner.nextInt();
System.out.println("Cantidad de dinero que se paga: ");
int dineroEntregado = scanner.nextInt();
int dineroDevuelto = dineroEntregado - dineroPorPagar;
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `CalculadoraDeCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto001/CalculadoraDeCambio.java) (Reto 001)

```java
Scanner scanner = new Scanner(System.in);
// ...
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `MinijuegoPelea.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto002/MinijuegoPelea.java) (Reto 002, líneas 4-6)

```java
final int DAÑO_ESPADA = 2;
int vidaGuerrero = 20;
final double PORCENTAJE_EXITO_GUERRERO = 0.5;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `CalculadoraDeCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto001/CalculadoraDeCambio.java) (Reto 001, líneas 35-36)

```java
int monedas1 = dineroDevuelto / 1;
dineroDevuelto = dineroDevuelto % 1;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `MinijuegoPelea.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3eaf8d2a0d715688103d9cb819d96a8a995dae38/entregas/masiasManuel/merinoAlberto/Reto002/MinijuegoPelea.java) (Reto 002, línea 13)

```java
boolean algunMuerto = false;
```

¿Qué observas en este código?

