# Examen Parcial - MarcosBoli

**Usuario GitHub:** MarcosBoli
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

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4d7909c8c0fd87d1f339f1f8445afe00b92ce200/entregas/bolivarMarcos/UnEdificio.java) (Reto 003)

```java
for (int hora = 0; hora <= 24; hora++) {
    // ...
    System.out.println("Dia "+dia+", Hora: "+hora+":00h");
}
```

¿Qué observas en este código?

---

## Pregunta 2

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4d7909c8c0fd87d1f339f1f8445afe00b92ce200/entregas/bolivarMarcos/UnEdificio.java) (Reto 003)

```java
for (int columna = 1; columna <= 7; columna++) {
    for (int fila = 1; fila <= 7; fila++) {
        if (fila == 4) {
            System.out.print(ASCENSOR);
        } else {
            System.out.print(LADRILLOS + ( ... ) + LADRILLOS);
            if(abierta && encendida){
                numeroEncendidas++;
                totalGastodia++;
            }
        }
    }
    System.out.println();
}
```

¿Qué observas en este código?

---

## Pregunta 3

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4d7909c8c0fd87d1f339f1f8445afe00b92ce200/entregas/bolivarMarcos/UnEdificio.java) (Reto 003)

```java
final double PROBABILIDAD_LUZ_ENCENDIDA = 0.5;
// ...
if(abierta && encendida){
    numeroEncendidas++;
}
```

¿Qué observas en este código?

---

## Pregunta 4

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4d7909c8c0fd87d1f339f1f8445afe00b92ce200/entregas/bolivarMarcos/UnEdificio.java) (Reto 003)

```java
final String LADRILLOS = ":";
// ...
System.out.print(LADRILLOS + (!abierta ? VENTANA_CERRADA : encendida ? LUZ_ENCENDIDA : LUZ_APAGADA) + LADRILLOS);
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4d7909c8c0fd87d1f339f1f8445afe00b92ce200/entregas/bolivarMarcos/UnEdificio.java) (Reto 003)

```java
System.out.println("El gasto total fue de: "+totalGastodia);
```

¿Qué observas en este código?

---

## Pregunta 6

Archivo: `CalculadoraDeCambio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4033432df806ebdcadd8d4d92da57704b50bbf5e/entregas/bolivarMarcos/reto001/CalculadoraDeCambio.java) (Reto 001)

```java
int costo;
costo = (int)(Math.random() * 100) + 1;
System.out.println("El total a pagar es: "+ costo);

Scanner Pago = new Scanner(System.in);
    System.out.println("Ingrese Con cuanto va a pagar: ");
int ingreso = Pago.nextInt();
```

¿Qué observas en este código?

---

## Pregunta 7

Archivo: `CalculadoraTiempo.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4033432df806ebdcadd8d4d92da57704b50bbf5e/entregas/bolivarMarcos/reto001/CalculadoraTiempo.java) (Reto 001)

```java
minutos = segundos / SEGUNDOS_POR_MINUTO;
horas = minutos / MINUTOS_POR_HORA;
dias = horas / HORAS_POR_DIA;

minutos = minutos >= MINUTOS_POR_HORA ? minutos % MINUTOS_POR_HORA : minutos;
horas = horas >= HORAS_POR_DIA ? horas % HORAS_POR_DIA : horas;
segundos = segundos >= SEGUNDOS_POR_MINUTO ? segundos % SEGUNDOS_POR_MINUTO : segundos;
```

¿Qué observas en este código?

---

## Pregunta 8

Archivo: `reto002.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/3adeba9cfb925185ab8953a36aeffb18ae9aa58c/entregas/bolivarMarcos/reto002/reto002.java) (Reto 002)

```java
if (numeroArmaEscogida == 5 && pocion) {
    turnoBloqueado = true;
    turnoActual = turno;
    pocion = false;
}
if (turno == turnoActual + 3) {
    turnoBloqueado = false;
    vidaHeroe = MAX_VIDA_HEROE;
    System.out.println("La vida del heroe se regeneró por completo!!");
}
```

¿Qué observas en este código?

---

## Pregunta 9

Archivo: `UnEdificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4d7909c8c0fd87d1f339f1f8445afe00b92ce200/entregas/bolivarMarcos/UnEdificio.java) (Reto 003)

```java
for (int fila = 1; fila <= 7; fila++) {
    abierta = Math.random() < PROBABILIDAD_PERSIANA_ABIERTA;
    encendida = Math.random() < PROBABILIDAD_LUZ_ENCENDIDA;
    if (fila == 4) {
        System.out.print(ASCENSOR);
    } else {
        System.out.print(
                LADRILLOS + (!abierta ? VENTANA_CERRADA : encendida ? LUZ_ENCENDIDA : LUZ_APAGADA)
                        + LADRILLOS);
        if(abierta && encendida){
            numeroEncendidas++;
            totalGastodia++;
        }
    }
}
```

¿Qué observas en este código?

---

## Pregunta 10

Archivo: `CalculadoraDePrecioFinal.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/4033432df806ebdcadd8d4d92da57704b50bbf5e/entregas/bolivarMarcos/reto001/CalculadoraDePrecioFinal.java) (Reto 001)

```java
PrecioUnitarioBase = (int) (Math.random() * 10000 + 100);

System.out.println("El precio unitario base del producto es de "+ PrecioUnitarioBase + " cts.");
Scanner imput = new Scanner(System.in);
    System.out.print("¿Que cantidad de artículos va a comprar?: ");
    cantidad = imput.nextInt();
```

¿Qué observas en este código?


