# Examen Parcial - richardnet539

**Usuario GitHub:** richardnet539
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

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/c88cfc08695130210c5b467312e1bc0037de160a/Entrega/reto-003/edificio.java) (Reto 003)

```java
public class edificio {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/c88cfc08695130210c5b467312e1bc0037de160a/Entrega/reto-003/edificio.java) (Reto 003)

```java
final double PERSIANA_ABIERTA = 0.7;
final double PERSIANA_CERRADA = 0.6;
// ...
encendida = Math.random() < PERSIANA_CERRADA;
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/c88cfc08695130210c5b467312e1bc0037de160a/Entrega/reto-003/edificio.java) (Reto 003)

```java
for (int hora = 0; hora <= 24; hora++) {
    System.out.println(" Son las " + hora + " del dia " + dia);
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/c88cfc08695130210c5b467312e1bc0037de160a/Entrega/reto-003/edificio.java) (Reto 003)

```java
System.out.print(!abierta ? VENTANA_CERRADA
             : encendida ? VENTANA_CON_LUZ_ENCENDIDA : VENTANA_CON_LUZ_APAGADA);
if (columna == 3) {
    System.out.print(separador);
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/c88cfc08695130210c5b467312e1bc0037de160a/Entrega/reto-003/edificio.java) (Reto 003)

```java
final String separador = "[    ]";
// ...
for (int fila = 1; fila <= 7; fila++) {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/888e795575faef5f0373d8bca3d23631398b9964/entrega/Ricardo%20Monteiro-reto001/CalculadoraDePrecioFinal.java) (Reto 001)

```java
double iva = CIEN_PORCIENTO / ivaIntroducido;

System.out.println(iva);
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/888e795575faef5f0373d8bca3d23631398b9964/entrega/Ricardo%20Monteiro-reto001/CalculadoraDePrecioFinal.java) (Reto 001)

```java
int descuento = cantidadDeUnidades >= CANTIDAD_DE_CIEN ? TIPO_DE_DESCUENTO_DE_QUINCE :
(cantidadDeUnidades >= CANTIDAD_DE_CINCUENTA ? TIPO_DE_DESCUENTO_DE_DIEZ :
(cantidadDeUnidades >= CANTIDAD_DE_CIEN  ?TIPO_DE_DESCUENTO_DE_CINCO : -1));
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `ConversorDeDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/888e795575faef5f0373d8bca3d23631398b9964/entrega/Ricardo%20Monteiro-reto001/ConversorDeDuracion.java) (Reto 001)

```java
int dias = totalSegundos / DIAS_EN_SEGUNDOS;
int horas = totalSegundos / HORAS_EN_SEGUNDOS;
int minutos = (totalSegundos % HORAS_EN_SEGUNDOS) / MINUTOS_EN_SEGUNDOS;
int segundos = totalSegundos % MINUTOS_EN_SEGUNDOS;
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/c88cfc08695130210c5b467312e1bc0037de160a/Entrega/reto-003/edificio.java) (Reto 003)

```java
for (int columna = 1; columna <= 6; columna++) {
    abierta = Math.random() < PERSIANA_ABIERTA;
    encendida = Math.random() < PERSIANA_CERRADA;
    System.out.print(!abierta ? VENTANA_CERRADA: encendida ? VENTANA_CON_LUZ_ENCENDIDA : VENTANA_CON_LUZ_APAGADA);
    if (columna == 3) {
        System.out.print(separador);
    }
}
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/888e795575faef5f0373d8bca3d23631398b9964/entrega/Ricardo%20Monteiro-reto001/CalculadoraDePrecioFinal.java) (Reto 001)

```java
double total = precioUnitarioBase + (precioUnitarioBase * iva );

double precioUnitarioFinal = total - (descuento * total);

System.out.println("Precio base: " + precioUnitarioBase + "$");
System.out.println(mensaje);
System.out.println("Precio unitario final: " + total + "$");
```

¿Qué observas en este código?


