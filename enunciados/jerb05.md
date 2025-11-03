# Examen Parcial - jerb05

**Usuario GitHub:** jerb05
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002, Reto 003

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

Archivo: `Batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/reto-002/Batalla.java) (Reto 002)

```java
} while (!algunMuerto);{
    // ...
    String elGanador = vidaGuerrero <=0 ? "El vampiro ha vencido al heroe" : "El heroe ha vencido al vampiro";
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Batalla2.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/reto-002/Batalla2.java) (Reto 002)

```java
else if (armaSeleccionada == 3) {
    if (Math.random() < PORCENTAJE_EXITO_ARMA_3)
        ;
    vidaVampiro = vidaVampiro - DAÑO_ARMA_3;
    System.out.println("El vampiro ha recibido " + DAÑO_ARMA_3 + " de daño!");
} else {
    System.out.println("El vampiro ha esquivado el ataque!");
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/src/CalculadoraDePrecioFinal.java) (Reto 001)

```java
double descuento;
descuento = (unidades >= 10) ? 0.95 : 1;
descuento = (unidades >= 50) ? 0.9: descuento;
descuento = (unidades >= 100) ? 0.85 : descuento;
double precioFinal;
precioFinal = IVA * descuento * precioBaseCentimos;
System.out.println ("IVA: " + 100 * (1-IVA) + "%");
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `CalculadoraDeCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/src/CalculadoraDeCambio.java) (Reto 001)

```java
int cambio = cantidadPagada - cantidadDebida;
int billetes100 = cambio / BILLETE_DE_100;
cambio = cambio % 100;
// ...
int monedas1 = cambio / MONEDA_DE_1;
cambio = cambio % 1;
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/reto-003/Edificio.java) (Reto 003)

```java
System.out.println("Dia " + dia + " - " + hora + ":00  Consumo hora: " + consumoDia);
System.out.println("Media semanal: " + (consumoTotalSemana / 7));
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/reto-003/Edificio.java) (Reto 003)

```java
class Edificio {

    public static void main(String[] args) {

    }

    final double PERSIANA_ABIERTA = 0.7;
    final double LUZ_ENCENDIDA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/reto-003/Edificio.java) (Reto 003)

```java
boolean abierta = Math.random() < PERSIANA_ABIERTA;
 {
    boolean encendida = Math.random() < LUZ_ENCENDIDA;

    String estadoVentana;
    if (!abierta)
        System.out.println(VENTANA_CERRADA);
        if (encendida){
            System.out.println(VENTANA_LUZ_ENCENDIDA);
            } else{

            }
                System.out.println(VENTANA_LUZ_APAGADA);
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/5d5f3f4e400252d3f4a5c90df45f1dff23d18240/entregas/riveraJorge/reto-002/Batalla.java) (Reto 002)

```java
do {
    if (Math.random() < PORCENTAJE_EXITO_GUERRERO) {
        vidaVampiro = vidaVampiro - DAÑO_ESPADA;
        System.out.println("El vampiro ha reicbido daño");
    } else {
```

¿Qué observas en este código?


