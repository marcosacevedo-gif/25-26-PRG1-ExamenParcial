# Examen Parcial - hugoastoreca-svg

**Usuario GitHub:** hugoastoreca-svg
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002, Reto 003

---

## Instrucciones

A continuación encontrarás fragmentos de código extraídos de tus entregas. Cada fragmento contiene una o más situaciones relacionadas con los conceptos vistos en clase.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 9 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `GuerreroVsVampiro.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-002/GuerreroVsVampiro.java) (Reto 001/PRG1)

```java
do {
    if (Math.random() < PORCENTAJE_EXITO_GUERRERO) {
        vidaVampiro -= DAÑO_ESPADA;
        System.out.println("El vampiro ha recibido");
    } else {
        System.out.println("El vampiro ha esquivado");
    }
    // ...
} while (!algunMuerto);
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `CalcularPrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-001/CalcularPrecioFinal.java) (Reto 001)

```java
double precioInicial = precioCentimos / 100.0;
double precioSinDescuento = precioInicial * cantidadProducto;
double precioConDescuento = precioSinDescuento - (precioSinDescuento * descuento / 100);
double precioFinal = precioConDescuento * (1 + tipoIVA / 100.0);
double precioTotal = precioFinal * cantidadProducto;
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `ConvertirDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-001/ConvertirDuracion.java) (Reto 001)

```java
final int DIAS_EN_SEGUNDOS = 86400;
final int HORAS_EN_SEGUNDOS = 3600;
final int MINUTOS_EN_SEGUNDOS = 60;
int dias = segundos / DIAS_EN_SEGUNDOS;
int horas = (segundos % DIAS_EN_SEGUNDOS) / HORAS_EN_SEGUNDOS;
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-003/Edificio.java) (Reto 003)

```java
System.out.println("TECHO_ALTO");
System.out.println("TECHO_MEDIO");
System.out.println("TECHO_BAJO");
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-003/Edificio.java) (Reto 003)

```java
System.out.print(!abierta ? VENTANA_CERRADA : (encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ));
if (columna == 3) {
    System.out.println(SEPARADOR);
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-003/Edificio.java) (Reto 003)

```java
System.out.println("Son las" +hora+ "del día"+dia) ;
System.out.println("TECHO_ALTO");
System.out.println("TECHO_MEDIO");
System.out.println("TECHO_BAJO");
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-003/Edificio.java) (Reto 003)

```java
} System.out.println("BASE");
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `ConvertirDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-001/ConvertirDuracion.java) (Reto 001)

```java
System.out.println ( minutos + "minutos");
System.out.println ( segundos + "segundos");
System.out.println ( horas + "horas");
System.out.println ( dias + "dias");
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `GuerreroVsVampiroExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/16fce73f7e86ff94ebff72fcb8be701559f96ba5/entregas/AstorecaHugo/reto-002/GuerreroVsVampiroExtendido.java) (Reto 002)

```java
int ataque = ((int) (Math.random() * 100)) % 3 + 1;
```

¿Qué observas en este código?


