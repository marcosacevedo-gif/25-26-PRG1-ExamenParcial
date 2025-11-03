# Examen Parcial - PabloWhite33

**Usuario GitHub:** PabloWhite33
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002

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

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/batalla.java) (Reto 002)

```java
class batalla {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/batalla.java) (Reto 002)

```java
System.out.print("¿Que arma quieres usar? (ESPADA = 7, ESCOPETA = 15, PISTOLA = 30): ");
int armaUsar = scanner.nextInt();
if (Math.random() < PORCENTAJE_EXITO_ESPADA) {
    vidaVampiro -= DAÑO_ESPADA_HEROE;
} else if (Math.random() < PORCENTAJE_EXITO_ESCOPETA) {
    vidaVampiro -= DAÑO_ESCOPETA_HEROE;
} else if (Math.random() < PORCENTAJE_EXITO_PISTOLA) {
    vidaVampiro -= DAÑO_PISTOLA_HEROE;
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/batalla.java) (Reto 002)

```java
final int MORDIDA_VAMPIRO = 5;
final int PATADA_VAMPIRO = 10;
final int PUÑETAZO_VAMPIRO = 20;
// ...
if (Math.random() < PORCENTAJE_EXITO_MORDIDA) {
    vidaGuerrero -= MORDIDA_VAMPIRO;
} else if (Math.random() < PORCENTAJE_EXITO_PATADA) {
    vidaGuerrero -= PATADA_VAMPIRO;
} else if (Math.random() < PORCENTAJE_EXITO_PUÑETAZO) {
    vidaGuerrero -= PUÑETAZO_VAMPIRO;
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/batalla.java) (Reto 002)

```java
System.out.println("Vida Guerrero [" + vidaGuerrero + "] / Vida Vampiro [" + vidaVampiro + "]");
String elGanador = vidaGuerrero > 0 ? "Guerrero" : "Vampiro";
System.out.println("Ganó el" + elGanador);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Calculadora de precio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/Calculadora%20de%20precio.java) (Reto 001)

```java
// (archivo con espacios en nombre y clases relacionadas)
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `Conversor de segundos.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/Conversor%20de%20segundos.java) (Reto 001)

```java
Scanner scanner = new Scanner(System.in);
System.out.print(s:"¿Cuantos segundos quieres convertir?");
int segundosTotales = scanner.nextInt();
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `Conversor de segundos.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/Conversor%20de%20segundos.java) (Reto 001)

```java
System.out.println(segundosTotales + "segundos son:");
System.out.println(dias + "días");
System.out.println(horas + "horas");
System.out.println(miutos + "minutos");
System.out.println(segundos + "segundos");
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/batalla.java) (Reto 002)

```java
System.out.print("¿Que arma quieres usar? (ESPADA = 7, ESCOPETA = 15, PISTOLA = 30): ");
int armaUsar = scanner.nextInt();

if (Math.random() < PORCENTAJE_EXITO_ESPADA) {
    vidaVampiro = vidaVampiro - DAÑO_ESPADA_HEROE;
    System.out.println("El guerrero ha acertado un golpe de ESPADA");
} else if (Math.random() < PORCENTAJE_EXITO_ESCOPETA) {
    vidaVampiro = vidaVampiro - DAÑO_ESCOPETA_HEROE;
    System.out.println("El guerrero ha acertado un golpe de ESCOPETA");
} else if (Math.random() < PORCENTAJE_EXITO_PISTOLA) {
    vidaVampiro = vidaVampiro - DAÑO_PISTOLA_HEROE;
    System.out.println("El guerrero ha acertado un golpe de PISTOLA");
} else {
    System.out.println("El guerrero ha fallado el golpe");
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3db4dfa0f2b4d0ba85a5119ccbd56f410ca73706/entregas/pablo.white/batalla.java) (Reto 002)

```java
if (Math.random() < PORCENTAJE_EXITO_MORDIDA) {
    vidaGuerrero = vidaGuerrero - MORDIDA_VAMPIRO;
    System.out.println("El guerrero recibe una MORDIDA");
} else if (Math.random() < PORCENTAJE_EXITO_PATADA) {
    vidaGuerrero = vidaGuerrero - PATADA_VAMPIRO;
    System.out.println("El guerrero recibe una PATADA");
} else if (Math.random() < PORCENTAJE_EXITO_PUÑETAZO) {
    vidaGuerrero = vidaGuerrero - PUÑETAZO_VAMPIRO;
    System.out.println("El guerrero recibe un PUÑETAZO");
} else {
    System.out.println("El guerrero esquiva");
}
```

¿Qué observas en este código?


