# Examen Parcial - rodrigorgo1909-web

**Usuario GitHub:** rodrigorgo1909-web
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001

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

Archivo: `Devolver cambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/Devolver%20cambio.java) (Reto 001)

```java
// Archivo con espacios en el nombre y ruta con acentos
```

¿Qué observas en este código/ruta?

---

## Pregunta 2

Archivo: `calculadora de precio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/calculadora%20de%20precio.java) (Reto 001)

```java
// Archivo con espacios en el nombre y clase relacionada
```

¿Qué observas en este código/ruta?

---

## Pregunta 3

Archivo: `conversor de segundos.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/conversor%20de%20segundos.java) (Reto 001)

```java
// Archivo con espacios; estructura esperable: lectura, descomposición, salida
```

¿Qué observas en este código/ruta?

---

## Pregunta 4

Archivo: `DevolucionCambio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Arodrigorgo1909-web+is%3Aall) (si procede)

```java
// Validaciones de entrada y uso de constantes para denominaciones
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `CalculadoraDePrecio.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Arodrigorgo1909-web+is%3Aall) (si procede)

```java
// Orden de aplicación descuento/IVA y tipos adecuados
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Devolver cambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/Devolver%20cambio.java) (Reto 001)

```java
final int Billete_100= 100;
final int Billete_50 = 50;
final int Billete_20 = 20;
final int Billete_10 = 10;
final int Billete_5 = 5;
final int Moneda_2 = 2;
final int Moneda_1= 1;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Devolver cambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/Devolver%20cambio.java) (Reto 001)

```java
int DineroAPagar = scanner.nextInt();
System.out.print("¿Con cuanto vas a pagar?");
int DineroUtilizado = scanner.nextInt();

int Cambio = DineroUtilizado - DineroAPagar;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `calculadora de precio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/calculadora%20de%20precio.java) (Reto 001)

```java
double precioConIva = precioEnEuros * (1 + tipoDeIva / 100.0);
double precioTotalAntesDescuento = precioConIva * cantidadDeArticulos;
double importeRebaja = precioTotalAntesDescuento * rebaja / 100.0;
double precioFinal = precioTotalAntesDescuento - importeRebaja;
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `conversor de segundos.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/conversor%20de%20segundos.java) (Reto 001)

```java
int dias = segundos / DIAS_EN_SEGUNDOS;
segundos = segundos % DIAS_EN_SEGUNDOS;

int horas = segundos / HORAS_EN_SEGUNDOS;
segundos = segundos % HORAS_EN_SEGUNDOS;

int minutos = segundos / MINUTOS_EN_SEGUNDOS;
segundos = segundos % MINUTOS_EN_SEGUNDOS;
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `conversor de segundos.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/1b566b8871e0ebc1e086b5d6513b1f24c7674e57/entregas/rodrigo.guti%C3%A9rrez/conversor%20de%20segundos.java) (Reto 001)

```java
System.out.println();
System.out.println("Resultado:");
System.out.println("Días: " + dias);
System.out.println("Horas: " + horas);
System.out.println("Minutos: " + minutos);
System.out.println("Segundos: " + segundos);
```

¿Qué observas en este código?

