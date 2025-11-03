# Examen Parcial - Extra 09

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

Archivo: `changeCalculator.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/256bd224386dfdcf63c87c9f57affdb807614668/entregas/bay%C3%B3nMateo/changeCalculator.java) (Reto 001, fragmento)

```java
int twoHundredBills = change > 200 ? change / 200 : 0;
change = change - (twoHundredBills * 200);

int oneHundredBills = change > 100 ? change / 100 : 0;
change = change - (oneHundredBills * 100);

int fiftyBills = change > 50 ? change / 50 : 0;
change = change - (fiftyBills * 50);
```

**Refactoriza este código:**

a) Elimina operadores innecesarios

b) Simplifica las operaciones

c) Muestra cómo quedaría una iteración mejorada

---

## Pregunta 2

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

## Pregunta 3

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

## Pregunta 4

Archivo: `edificio.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/c88cfc08695130210c5b467312e1bc0037de160a/Entrega/reto-003/edificio.java) (Reto 003)

```java
for (int hora = 0; hora <= 24; hora++) {
    System.out.println(" Son las " + hora + " del dia " + dia);
}
```

¿Qué observas en este código?

---

## Pregunta 5

Archivo: `Reto_003.java` — [Ver archivo](https://github.com/mmasias/25-26-PRG1/blob/6fe0288c85b7cec67a50fecda28e783147b118ff/entregas/Reto_003.java) (Reto 003, línea 30)

```java
System.out.print(!abierta ? VENTANA_CERRADA : encendida ? VENTANA_ABIERTA_CON_LUZ : VENTANA_ABIERTA_SIN_LUZ);
```

¿Qué observas en este código?

