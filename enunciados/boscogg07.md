# Examen Parcial - boscogg07

**Usuario GitHub:** boscogg07
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002, Reto 003

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

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/CalculadoraDePrecioFinal.java) (Reto 001)

```java
double euros = centimos / 100;
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/CalculadoraDePrecioFinal.java) (Reto 001)

```java
double descuento = 0;
descuento = unidades < 10 ? DESCUENTO1 : (unidades < 50 ? DESCUENTO2 : (unidades < 100 ? DESCUENTO3 : DESCUENTO4));
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `CalculadoraCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/CalculadoraCambio.java) (Reto 001)

```java
int resto = vuelta % 100;
int cociente = vuelta / 100;
System.out.println(cociente + " billete(s) de 100 euros");
// ... (se reusa cociente/resto)
System.out.println(resto + " moneda(s) de 1 euros");
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `ConversorDeDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/ConversorDeDuracion.java) (Reto 001)

```java
final int SEGUNDO_DE_HORA = 60 * 60;
// ...
segundos = segundos % (SEGUNDO_DE_HORA);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Reto_003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/Reto_003.java) (Reto 003)

```java
for (int dia = 1; dia < 7; dia++) {
    for (int hora = 0; hora < 24; hora++) {
        System.out.println("Son las " + hora + " del día " + dia);
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Reto_002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/Reto_002.java) (Reto 002, líneas 23-27)

```java
boolean algunMuerto = false;
boolean guerreroVivo = true;
boolean vampiroVivo = true;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Reto_002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/Reto_002.java) (Reto 002, líneas 31-48)

```java
if (arma == 1) {
    if (Math.random() < PROBABILIDAD_ARMA1) {
        vidaVampiro = vidaVampiro - ARMA1;
        System.out.println("El vampiro recibe daño del arma1");
    } else {
        System.out.println("El vampiro esquiva el arma1");
    }

} else if (arma == 2) {
    if (Math.random() < PROBABILIDAD_ARMA2) {
        vidaVampiro = vidaVampiro - ARMA2;
        System.out.println("El vampiro recibe daño del arma2");
    } else {
        System.out.println("El vampiro esquiva el arma2");
    }
}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Reto_003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/Reto_003.java) (Reto 003, línea 30)

```java
System.out.print(!abierta ? VENTANA_CERRADA : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/CalculadoraDePrecioFinal.java) (Reto 001, líneas 5-11)

```java
final double GENERAL = 0.21;
final double REDUCIDO = 0.1;
final double SUPER_REDUCIDO = 0.04;
final double DESCUENTO1 = 0;
final double DESCUENTO2 = 0.05;
final double DESCUENTO3 = 0.1;
final double DESCUENTO4 = 0.15;
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `ConversorDeDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/ConversorDeDuracion.java) (Reto 001, línea 26)

```java
System.out.println(dias + " dia" + (dias > 1 ? "s" : ""));
```

¿Qué observas en este código?

