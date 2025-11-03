# Examen Parcial - Asiergarrastazu

**Usuario GitHub:** Asiergarrastazu
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 003

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

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003)

```java
final String VENATANA_ABIERTA_SIN_LUZ = "[º]";
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003)

```java
for (int hora =0 ; hora <24; hora++){
    System.out.println("Son las" + hora + "en el dia" +dia );
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003)

```java
for (int planta=1 ; planta <=7; planta++) {
  for (int columna=1 ; columna <=6; columna++) {
      abierta =Math.random() < PERSIANA_ABIERTA;
      encendida =Math.random() < LUZ_ENCENDIDA;
      System.out.println(!abierta ? VENTANA_CERRADA: (encendida ? VENTANA_ABIERTA_CON_LUZ: VENATANA_ABIERTA_SIN_LUZ));
  }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003)

```java
final String BASE = "------------------------------------";
// ...
System.out.println(BASE);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003)

```java
public class Edificio {
    public static void main(String[] args) {
        // ...
        }
       }
    }
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003, líneas 8-10)

```java
final String VENTANA_CERRADA = "[ ]";
final String VENTANA_ABIERTA_CON_LUZ = "[*]";
final String VENATANA_ABIERTA_SIN_LUZ = "[º]";
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003, líneas 26-32)

```java
for (int planta=1 ; planta <=7; planta++) {
    for (int columna=1 ; columna <=6; columna++) {
        abierta =Math.random() < PERSIANA_ABIERTA;
        encendida =Math.random() < LUZ_ENCENDIDA;
        System.out.println(!abierta ? VENTANA_CERRADA: (encendida ? VENTANA_ABIERTA_CON_LUZ: VENATANA_ABIERTA_SIN_LUZ));

}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003, línea 31)

```java
System.out.println(!abierta ? VENTANA_CERRADA: (encendido ? VENTANA_ABIERTA_CON_LUZ: VENATANA_ABIERTA_SIN_LUZ));
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4ef44509e8dbfe2d9cf69657c548d5aa338d2707/entregas/asierGarrastazu/reto-003/Edificio.java) (Reto 003, líneas 17-19)

```java
boolean abierta;
boolean encendida;
for (int dia =1 ; dia <=30; dia++) {
```

¿Qué observas en este código?


