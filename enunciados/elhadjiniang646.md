# Examen Parcial - elhadjiniang646

**Usuario GitHub:** elhadjiniang646
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

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
final double PERSIANA_ABIERTA = 0.7;
final double PERSIANA_CERRADA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
for (int i = 0; i <= horasTotales; i++) {
    abierta = Math.random() < PERSIANA_ABIERTA;
    encendida = Math.random() < PERSIANA_CERRADA;
    hora++;
    if (hora == 24) {
        hora = 1;
        dia = dia + 1;
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
for (int piso = 1; piso < 7; piso++) {
    for (int columna = 1; columna < piso; columna++) {
        System.out.print(!abierta ? VENTANA_CERRADA : encendida ? LUZ_ENCENDIDA : LUZ_APAGADA );
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
System.out.println("Dia " + dia + " - " + hora + ":00h ");
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
class Edificio {
    public static void main(String[] args) {
        // ...
        };
    };
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
for (int i = 0; i <= horasTotales; i++) {
    abierta = Math.random() < PERSIANA_ABIERTA;
    encendida = Math.random() < PERSIANA_CERRADA;

    hora++;

    if (hora == 24) {
        hora = 1;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
for (int piso = 1; piso < 7; piso++) {
    for (int columna = 1; columna < piso; columna++) {
        System.out.print(!abierta ? VENTANA_CERRADA : encendida ? LUZ_ENCENDIDA : LUZ_APAGADA );
    }
    ;
}
;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
System.out.println(

           "------------------------------------\r\n" +
            "     ==========================\r\n" +
            "   ==============================\r\n" +
         " ==================================\r\n" +

            "Dia " + dia + " - " + hora + ":00h ");
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/bca521c60726a8fabc73ebc9281552231873d9fb/entregas/elhadjiNiang/src/reto003/Edificio.java) (Reto 003)

```java
for (int i = 0; i <= horasTotales; i++) {
    abierta = Math.random() < PERSIANA_ABIERTA;
    encendida = Math.random() < PERSIANA_CERRADA;
    // ...
}
};
```

¿Qué observas en este código?


