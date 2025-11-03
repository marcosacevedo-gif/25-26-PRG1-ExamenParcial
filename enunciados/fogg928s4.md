# Examen Parcial - fogg928s4

**Usuario GitHub:** fogg928s4
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

Archivo: `EdificioEnLaSemana.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ec637ba447a91c88c6b9ef4161a464cbc2d26250/entregas/melgaresjose/src/retoBase/EdificioEnLaSemana.java) (Reto 003)

```java
for(int i = 1; i < DIAS_EN_SEMANA*HORAS_EN_DIA; i++) {
    // ...
    numeroDia = (int) (i / HORAS_EN_DIA) + 1;
    numeroHora = (i % HORAS_EN_DIA);
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `EdificioEnLaSemana.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ec637ba447a91c88c6b9ef4161a464cbc2d26250/entregas/melgaresjose/src/retoBase/EdificioEnLaSemana.java) (Reto 003)

```java
final int PLANTAS_HABITACIONES = 7;
final int HABITACIONES_POR_PLANTA = 6;
// ...
for(int planta = PLANTAS_HABITACIONES; planta>= 1; planta-- ){
    for(int habitacion = 1; habitacion <= HABITACIONES_POR_PLANTA; habitacion++) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `EdificioEnLaSemana.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ec637ba447a91c88c6b9ef4161a464cbc2d26250/entregas/melgaresjose/src/retoBase/EdificioEnLaSemana.java) (Reto 003)

```java
if(!estaAbierta) {
    System.out.print(PERSIANA_CERRADA);
}
else {
    System.out.print(luzEstaEncendida ? LUZ_ENCENDIDA : LUZ_APAGADA);
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `EdificioEnLaSemana.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ec637ba447a91c88c6b9ef4161a464cbc2d26250/entregas/melgaresjose/src/retoBase/EdificioEnLaSemana.java) (Reto 003)

```java
System.out.print(habitacion == 3 ? COLUMNA_CENTRAL: "");
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `EdificioEnLaSemana.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ec637ba447a91c88c6b9ef4161a464cbc2d26250/entregas/melgaresjose/src/retoBase/EdificioEnLaSemana.java) (Reto 003)

```java
System.out.println("Dia: " + numeroDia + " hora: " + numeroHora+ ":00");
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `EdificioEnLaSemana.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/ec637ba447a91c88c6b9ef4161a464cbc2d26250/entregas/melgaresjose/src/retoBase/EdificioEnLaSemana.java) (Reto 003)

```java
boolean estaAbierta = false;
boolean luzEstaEncendida = false;
int numeroDia;
int numeroHora;
for(int i = 1; i < DIAS_EN_SEMANA*HORAS_EN_DIA; i++) {
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `PeleaVampiro.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6b16a7fd804f205cf872e900eab65b5beca9e057/entregas/melgaresjose/src/parte1/PeleaVampiro.java) (Reto 002)

```java
hayMuerto = vampiroHP * guerreroHP <= 0;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `PeleaExtendida.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6b16a7fd804f205cf872e900eab65b5beca9e057/entregas/melgaresjose/src/extendido/PeleaExtendida.java) (Reto 002)

```java
System.out.println(dadoVampiro ? " y ha hecho al guerrero": "... pero fallo");
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `MaquinaDeCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/613a8a347054482b6335ab8cee0797a4f096fb30/entregas/melgaresJose/src/MaquinaDeCambio/MaquinaDeCambio.java) (Reto 001)

```java
int cambio = eurosAPagar - eurosRecibidos;
cambio = cambio * (cambio < 0 ? -1 : 1);
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `PeleaConDefensa.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6b16a7fd804f205cf872e900eab65b5beca9e057/entregas/melgaresjose/src/adicional1/PeleaConDefensa.java) (Reto 002)

```java
danoBase = seDefiendeGuerrero ? (DANO_TORTURA-5) : DANO_TORTURA;
```

¿Qué observas en este código?


