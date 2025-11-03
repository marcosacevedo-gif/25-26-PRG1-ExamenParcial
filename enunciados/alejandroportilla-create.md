# Examen Parcial - alejandroportilla-create

**Usuario GitHub:** alejandroportilla-create
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Reto 001, Reto 002, Reto 003

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

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/reto-003/Edificio.java) (Reto 003)

```java
final double PERSIANA_ABIERTA = 0.7;
final double LUZ_ENCENCIDA = 0.6;
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/reto-003/Edificio.java) (Reto 003)

```java
for (int hora=0; hora<=24; hora++) {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `Edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/reto-003/Edificio.java) (Reto 003)

```java
for (int planta=1; planta<=7; planta++) {
    for (int columna=1; columna<=6; columna++) {
        abierta = Math.random() < PERSIANA_ABIERTA;
        encendida = Math.random() < LUZ_ENCENCIDA;
        System.out.println(!abierta ? VENTANA_CERRADA : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
        if (columna == 3 ) {
            System.out.print( SEPARADOR );
        }
    }
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `CalcularPrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/Reto-001/CalcularPrecioFinal.java) (Reto 001)

```java
double descuento = 0.0;
if (cantidad >= 10) {
    descuento = 0.05;
}
if (cantidad >= 50) {
    descuento = 0.10;
}
if (cantidad >= 100) {
    descuento = 0.15;
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `DevolverCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/Reto-001/DevolverCambio.java) (Reto 001)

```java
int pagar = lector.nextInt();
int paga = lector.nextInt();
int cambio = paga - pagar;
// ...
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `DevolverCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/Reto-001/DevolverCambio.java) (Reto 001, líneas 36-38)

```java
int monedas1 = cambio / 1;
cambio = cambio % 1;
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `BatallaHeroeVampirosextendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/reto-002/BatallaHeroeVampirosextendido.java) (Reto 002, línea 95)

```java
String elGanador = vidaGuerrero > 0 ? "Guerrero" : "Vampiro";System.out.println("Ganó el "+elGanador);
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `BatallaHeroeVampirosextendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/reto-002/BatallaHeroeVampirosextendido.java) (Reto 002, líneas 31-48)

```java
if(arma == 1){
    if(Math.random()<PROBABILIDAD_ARMA1){
    vidaVampiro = vidaVampiro - ARMA1;
    System.out.println("El vampiro recibe daño");
    }else{
         System.out.println("El vampiro esquiva");
    }

}else if(arma==2){
   if(Math.random()<PROBABILIDAD_ARMA2){
    vidaVampiro = vidaVampiro - ARMA2;
    System.out.println("El vampiro recibe daño");
   }else{
    System.out.println("El vampiro esquiva");
   }
}else if(arma==3){
    if(Math.random()<PROBABILIDAD_ARMA3){
        vidaVampiro = vidaVampiro - ARMA3;
        System.out.println("El vampiro recibe daño");
    }else{
        System.out.println("El vampiro esquiva");
    }
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `BatallaHeroeVampirosextendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/a4a32c7cefe2fbbb8310e3d8b6906a453b3ec346/entregas/PortillaAlejandro/reto-002/BatallaHeroeVampirosextendido.java) (Reto 002, líneas 25-27)

```java
boolean algunMuerto = false;
boolean guerreroVivo = true;
boolean vampiroVivo = true;
```

¿Qué observas en este código?

