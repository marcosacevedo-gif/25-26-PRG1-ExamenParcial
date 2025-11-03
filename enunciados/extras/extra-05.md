# Examen Parcial - Extra 05

**Fecha:** 4 de noviembre de 2025

---

## Instrucciones

A continuación encontrarás 5 fragmentos de código extraídos de exámenes reales de tus compañeros.

Para cada pregunta debes:
1) Identificar a qué se refiere la observación
2) Explicar si es o no un error y por qué
3) Proponer la corrección

Nota: Responde 5 de las 5 preguntas (elige libremente).


---

## Pregunta 1

Archivo: `HotelLuces.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/0940bca38a3852dfc71939340aea56c2d6eddd4b/entregas/arroyosanchezdaniel/HotelLuces.java) (Reto 003)

```java
final String VENTANA_CERRADA = ":[ ]:";
final String LUZ_APAGADA = ":[º]:";
final String LUZ_ENCENDIDA = ":[*]:";
```

¿Qué observas en este código?

---

## Pregunta 2

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

## Pregunta 3

Archivo: `Batalla.java` — [PRs del alumno](https://github.com/mmasias/25-26-PRG1/pulls?q=is%3Apr+author%3Amarcosruiz-glitch+is%3Aall) (Reto 002)

```java
do {

    if (Math.random() < PORCENTAJE_EXITO_GUERRERO) {
        vidaVampiro = vidaVampiro - DAÑO_ESPADA;
        System.out.println("¡El vampiro recibe la ostia!");
    } else {
        System.out.println("¡El vampiro esquiva la ostia!");
    }

    boolean vampiroVivo = vidaVampiro > 0;
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a57f109ee798efd2f5a3e197f889465a3e4cbe28/entregas/gonzalesDiego/src/Edificio.java) (Reto 003)

```java
for (int dia = 1; dia <= 7; dia++) {
    for (int hora = 0; hora < 24; hora++) {
        System.out.println("Son las " + hora + " horas del dia" + dia);
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/b6839e92164766d6a4b5d2a8764e272be2c3b399/entregas/javierrodriguezrobles07-creator/edificio.java) (Reto 003)

```java
while (dia <= DIAS) {
    int consumoDia = 0;
    int hora = 0;
    while (hora < HORAS) {
        // ...
        hora++;
    }
}
System.out.println("Media semanal: " + (consumoTotalSemana / 7));
```

¿Qué observas en este código?

