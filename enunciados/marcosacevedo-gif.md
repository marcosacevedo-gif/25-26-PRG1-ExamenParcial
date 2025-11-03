# Examen Parcial - marcosacevedo-gif

**Usuario GitHub:** marcosacevedo-gif
**Fecha:** 4 de noviembre de 2025
**Retos tenidos en cuenta:** Ejercicios, Reto 001, Reto 002, Reto 003

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

Archivo: `ClasificacionEdades.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/ClasificacionEdades.java) (Ejercicios)

```java
if (edad < EDAD_INFANCIA) {
    // ...
} else if (edad < EDAD_ADOLESCENCIA && edad > EDAD_NIÑO) {
    // ...
} else if (edad < EDAD_JOVEN && edad > EDAD_INFANCIA) {
    // ...
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `PiedraPapelTijera.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/PiedraPapelTijera.java) (Ejercicios)

```java
class juego {
    public static void main(String[] args) {
        // ...
    }
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `CalcularPrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-001/CalcularPrecioFinal.java) (Reto 001)

```java
// entrada de datos -> cálculo -> salida
// (usa variables como precioBaseCentimos, cantidad, iva y descuentos escalonados)
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `BatallaHeroeVampirosextendido.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-002/BatallaHeroeVampirosextendido.java) (Reto 002)

```java
int opcion = scanner.nextInt();
int ataqueHeroe = 0;
double probExitoHeroe = 0.0;
if (opcion == 1) { ataqueHeroe = 7; probExitoHeroe = 0.5; }
else if (opcion == 2) { ataqueHeroe = 15; probExitoHeroe = 0.25; }
else if (opcion == 3) { ataqueHeroe = 30; probExitoHeroe = 0.12; }
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-003/edificio.java) (Reto 003)

```java
for (int hora=0; hora<=24; hora++) {
    System.out.println("Son las " +  hora + " del dia " + dia);
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
}
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `ClasificacionEdades.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/ClasificacionEdades.java) (Reto 003)

```java
else if (edad < EDAD_ADOLESCENCIA && edad > EDAD_NIÑO) {
    System.out.println("Usted está en la infancia");
}
else if (edad < EDAD_JOVEN && edad > EDAD_INFANCIA) {
    System.out.println("Usted es un adolescente");
}
else if (edad < EDAD_ADULTO && edad > EDAD_ADOLESCENCIA) {
    System.out.println("Usted es un joven");
}
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `GeneradorRandomNumeros.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/Prog1/retos/GeneradorRandomNumeros.java) (Reto 003)

```java
int numeroAleatorio=(int) (Math.random()*100)+1;
System.out.println("Introduce la cantidad de números aleatorios a generar:");

for (int i = 0; i < 10; i++) {
    numeroAleatorio = (int) (Math.random() * 100) + 1;
    System.out.println(numeroAleatorio);
}
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `ConvertirDuracion.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-001/ConvertirDuracion.java) (Reto 001)

```java
int segundosTotales;
int dias, horas, minutos, segundos;

System.out.println("¿Cuántos segundos desea convertir?");
segundosTotales = teclado.nextInt();

dias = segundosTotales / 86400;
segundosTotales = segundosTotales % 86400;

horas = segundosTotales / 3600;
segundosTotales = segundosTotales % 3600;
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `BatallaHeroeVampirosbase.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/entregas/AcevedoMarcos/Reto-002/BatallaHeroeVampirosbase.java) (Reto 002)

```java
int vidaVampiro = 10;
final double PORCENTAJE_EXITO_VAMPIRO = 0.5;
final int DAÑO_ESPADA = 2;

int vidaGuerrero = 10;
final double PORCENTAJE_EXITO_GUERRERO = 0.5;
final int DAÑO_MORDIDA = 4;
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `PiedraPapelTijera.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/800caa907f89e594d366a3e24ace25b5ca7cc251/PiedraPapelTijera.java) (Reto 003)

```java
int ordenador = (int) (Math.random() * 3) + 1;
System.out.println("El ordenador ha elegido: " + ordenador);
```

¿Qué observas en este código?


