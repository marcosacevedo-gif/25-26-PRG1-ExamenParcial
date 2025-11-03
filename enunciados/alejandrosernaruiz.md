# Examen Parcial - alejandrosernaruiz

**Usuario GitHub:** alejandrosernaruiz
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

Archivo: `reto002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/reto002.java) (Reto 002)

```java
if(aciertaGuerrero){
    hpVampiro= hpVampiro-dañoGuerrero;
    System.out.println("El guerrero acirta y hace "+dañoGuerrero);
} else {
    hpVampiro=hpVampiro;
    System.out.println("El guerrero ha fallado el golpe");
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `reto002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/reto002.java) (Reto 002)

```java
int ronda=1;
while(hpGuerrero>0&&hpVampiro>0){
    System.out.println("--------RONDA "+ronda+"-------");
    // ...
    ronda++;
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/reto003.java) (Reto 003)

```java
for (int piso = PISOS - 1; piso >= 1; piso--) {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `reto001.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/retos/reto001.java) (Reto 001)

```java
Scanner scanner = new Scanner(System.in);
int precioPagar = scanner.nextInt();
Scanner scanner2 = new Scanner(System.in);
int dineroEntregado = scanner2.nextInt();
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `reto001.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/retos/reto001.java) (Reto 001)

```java
int[] billetes={100,50,20,10,5,2,2};
String[] nombres={"billete(s) de 100", "billete(s) de 50", "billete(s) de 20",
                  "billete(s) de 10", "billete(s) de 5", "moneda(s) de 2", "moneda(s) de 1"};
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `reto002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/reto002.java) (Reto 002, líneas 5-7)

```java
int hpGuerrero = 20;
int dañoGuerrero = 2;
int hpVampiro = 10;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `reto002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/reto002.java) (Reto 002, líneas 23-24)

```java
else{
    hpVampiro=hpVampiro;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `reto003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6230b7b966f32b52a8202521079a8787abe93d0a/evaluaciones/reto003.java) (Reto 003, líneas 3-6)

```java
public class reto003{
static final int PISOS = 8;
    static final int HABITACIONES_POR_PISO = 8;
```

¿Qué observas en este código?


