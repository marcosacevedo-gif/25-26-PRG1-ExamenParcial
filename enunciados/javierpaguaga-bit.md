# Examen Parcial - javierpaguaga-bit

**Usuario GitHub:** javierpaguaga-bit
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 003

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

Archivo: `SimulacionDeHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotel.java) (Reto 003)

```java
for(int hora=0;hora<=24;hora++) {
    // ...
    System.out.println("Día " + dia + ", Hora " + hora + ":00h");
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `SimulacionDeHotel.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotel.java) (Reto 003)

```java
final String VENTANA_ABIERTA_LUZ_APAGADO = ":[o]:";
final double PROBABILIDAD_LUZ_Encendido = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `SimulacionDeHotelExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotelExtendido.java) (Reto 003)

```java
int Comsumo = 0;
// ...
Comsumo = Comsumo + (encendida ? 1 : 0);
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `SimulacionDeHotelExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotelExtendido.java) (Reto 003)

```java
boolean yaPasoMantenimiento = false;
boolean enMantenimiento;
// ...
if (enMantenimiento){
    yaPasoMantenimiento = true;
    enMantenimiento = false;
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `SimulacionDeHotelExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotelExtendido.java) (Reto 003)

```java
int comsumaSemanal = (D1 + D2 + D3 + D4 + D5 + D6 + D7);
System.out.println("Media de consumo semanal: " + (comsumaSemanal /7));
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `SimulacionDeHotelExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotelExtendido.java) (Reto 003)

```java
int D1 = 0, D2 = 0, D3 = 0, D4 = 0, D5 = 0, D6 = 0, D7 = 0;
int Comsumo = 0;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `SimulacionDeHotelExtendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/924b80e37c0a5708a04d4286b77fa398b36f25f8/entregas/paguagaJavier/reto-003/SimulacionDeHotelExtendido.java) (Reto 003)

```java
switch (dia) {
    case 1 -> D1 = Comsumo;
    case 2 -> D2 = Comsumo;
    case 3 -> D3 = Comsumo;
    case 4 -> D4 = Comsumo;
    case 5 -> D5 = Comsumo;
    case 6 -> D6 = Comsumo;
    case 7 -> D7 = Comsumo;
}
```

¿Qué observas en este código?


