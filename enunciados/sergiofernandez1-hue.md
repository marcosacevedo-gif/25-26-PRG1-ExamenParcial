# Examen Parcial - sergiofernandez1-hue

**Usuario GitHub:** sergiofernandez1-hue
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 002

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

Archivo: `Batalla Extendida.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/Batalla%20Extendida.java) (Reto 002)

```java
class batallaExtendida {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Batalla Extendida.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/Batalla%20Extendida.java) (Reto 002)

```java
switch (ataqueElegidoGuerrero){
  case 1 -> { /* ... */ }
  case 2 -> { /* ... */ }
  case 3 -> { /* ... */ }
}
if (vidaVampiro <= 0){
    vampiroVivo = false;
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Batalla Extendida.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/Batalla%20Extendida.java) (Reto 002)

```java
eleccionAtaqueVampiro = Math.random();
if (eleccionAtaqueVampiro <= PROBABILIDAD_ELECCION_ATAQUE_1){
    // ...
} else if (eleccionAtaqueVampiro >= PROBABILIDAD_ELECCION_ATAQUE_1 && eleccionAtaqueVampiro <= PROBABILIDAD_ELECCION_ATAQUE_2){
    // ...
} else {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/batalla.java) (Reto 002)

```java
if (caballeroVivo == true){ /* ... */ }
// ...
if (vampiroVivo == true){ /* ... */ }
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/batalla.java) (Reto 002)

```java
System.out.println("Turno del guerrero, con " + vidaGuerrero + " puntos de vida");
// ... lógica de turno y fin de lazo
if (vidaGuerrero <= 0 || vidaVampiro <= 0) {
    algunMuerto = true;
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/batalla.java) (Reto 002)

```java
if (caballeroVivo == true){
    System.out.println("Turno del guerrero, con " + vidaGuerrero + " puntos de vida");
    probabilidadGolpe = Math.random();
    if (probabilidadGolpe >= PORCENTAJE_EXITO_GUERRERO){
        vidaVampiro = vidaVampiro - DAÑO_ESPADA;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `batalla.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/batalla.java) (Reto 002)

```java
if (vidaVampiro <=0){
    vampiroVivo = false;
    System.out.println("El vampiro ha muerto");
}
} else {
    System.out.println("El vampiro ha conseguido esquivar el ataque");
}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `Batalla Extendida.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/Batalla%20Extendida.java) (Reto 002)

```java
while (ataqueElegidoGuerrero != 1 && ataqueElegidoGuerrero != 2 && ataqueElegidoGuerrero != 3){
    System.out.println("Elige el ataque: \n [1] Ataque cuchillo \n [2] Ataque espada \n [3] Ataque hacha");
    ataqueElegidoGuerrero = scanner.nextInt();
    if(ataqueElegidoGuerrero != 1 && ataqueElegidoGuerrero != 2 && ataqueElegidoGuerrero != 3){
        System.out.println("El guerrero no conoce ese ataque");
    }
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `Batalla Extendida.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/Batalla%20Extendida.java) (Reto 002)

```java
eleccionAtaqueVampiro = Math.random();
if (eleccionAtaqueVampiro <= PROBABILIDAD_ELECCION_ATAQUE_1){
    System.out.println("El vampiro trata de atacar al guerrero con sus garras");
    probabilidadGolpe = Math.random();
    if (probabilidadGolpe <= PORCENTAJE_EXITO_VAMPIRO_ATAQUE_1){
        vidaGuerrero = vidaGuerrero - DAÑO_MORDIDA1;
        System.out.println("El vampiro ha herido al guerrero con -" + DAÑO_MORDIDA1 + " puntos de vida");
    }else{
        System.out.println("El guerrero ha conseguido esquivar el ataque");
    }

}else if (eleccionAtaqueVampiro >= PROBABILIDAD_ELECCION_ATAQUE_1 && eleccionAtaqueVampiro <= PROBABILIDAD_ELECCION_ATAQUE_2){
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `Batalla Extendida.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a15cf8e4fdd5b0802206f86a21acbc3c90357a6a/entregas/sergio.fernandez/reto-002/Batalla%20Extendida.java) (Reto 002)

```java
switch (ataqueElegidoGuerrero){

    case 1 -> {
        probabilidadGolpe = Math.random();
        if (probabilidadGolpe <= PORCENTAJE_EXITO_GUERRERO_CUCHILLO){
            vidaVampiro = vidaVampiro - DAÑO_CUCHILLO;
            System.out.println("El guerrero ha herido al vampiro con -" + DAÑO_CUCHILLO + " puntos de vida");
        }else{
            System.out.println("El vampiro ha conseguido esquivar el ataque");
        }
    }
```

¿Qué observas en este código?


