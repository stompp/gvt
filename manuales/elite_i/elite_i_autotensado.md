# Motor Elite-i Autotensado. Manual de instalación

Texto en español del manual de Gaviota (REF. 4004-0668, 06-20), sacado de `raw/gvt/motores_y_automatismos/elite/manuales/Manual Motor Elite-i Autotensado - ES_GB_FR_IT_DE.PDF`. Entre paréntesis, la página del PDF. Modelo: `elite_i_autotensado`.

## Advertencias de seguridad (p. 2)

Leer las instrucciones antes de usar el producto y conservarlas. No respetar las instrucciones de montaje, uso y especificaciones, o exceder los rangos de uso (pesos, etc.), excluye el producto de la política de garantía y del servicio posventa de Gaviota Simbac.

## 01 Descripción del producto (p. 5)

Los motores de la línea Elite-i Autotensado llevan un final de carrera electrónico vía radio. Se controlan con emisores, sensores radio y la aplicación móvil. Los puntos de parada y el sentido de giro se programan con el emisor. Solo reciben señales de los emisores y sensores Elite-i de Gaviota. (El manual no dice para qué sistemas está diseñado.)

## Emisores compatibles (p. 6)

Emisor 1 canal Elite-i, emisor 15 canales Elite-i, emisor pared 1 canal Elite-i, emisor pared 15 canales Elite-i, sensor de movimiento Elite-i, módulo CONNECT, central sol viento Elite-i y central sol viento Elite-i inalámbrica.

## Conexiones (p. 7)

| Hilo | Color |
| --- | --- |
| 1 | Amarillo (amarillo-verde): tierra |
| 2 | Azul: neutro |
| 3 | Marrón: fase |

## Indicaciones previas a la programación (p. 8)

- Si entre los pasos de la asignación de emisor pasan más de 10 segundos, hay que quitar la alimentación y empezar de nuevo.
- Con varios motores, se programan alimentándolos de uno en uno.
- En los emisores de 15 canales el canal 0 es solo funcional: se deja libre de programaciones.
- En todos los emisores el botón «P2» está en la parte trasera.
- Durante la programación de los finales de carrera el motor funciona a pulsaciones: hay que mantener 2 segundos el botón del sentido en el que se quiere mover. Si funciona de forma continua, los finales ya están programados.

## 06.3 Modificación de los finales de carrera (p. 15)

No se puede modificar un solo final de carrera: hay que modificar los dos. Para ello: borrar los finales (06.2), programar el de subida (06.1.1) y programar el de bajada (06.1.2).

## 10 Borrado completo del motor (p. 23)

Hay que hacer los dos puntos: borrar los finales de carrera (06.2) y eliminar todos los emisores (08.3). Si no se hace uno de ellos, se conserva su programación.

## Procedimientos

Cómo responde el equipo: un **movimiento** es un pequeño giro de subida y bajada del motor; un **pitido** es la señal sonora. «P2» es el botón de la parte trasera del emisor.

### 04 Asignar el primer emisor al motor (pp. 9-10)

Condición previa: Motor recién alimentado; menos de 10 s entre pasos; con varios motores, alimentar uno cada vez.

1. (motor) Dar corriente: **Sin emisores: 1 movimiento y 1 pitido; con un emisor programado: 1 movimiento**.
2. (emisor nuevo) «P2» 1 s: **1 movimiento y 1 pitido**.
3. (emisor nuevo) «P2» 1 s: **1 movimiento y 1 pitido**.
4. (emisor nuevo) «Subida»: **2 movimientos y 3 pitidos**.

Si el motor ya tenía emisor (respuesta B), el reconocimiento conserva su estado: sentido de giro, emisores y finales de carrera. En los emisores de 15 canales el canal 0 es solo funcional: no se programa.

### 05 Invertir el sentido de giro (p. 11)

Condición previa: Sin finales de carrera programados.

1. (emisor programado) «Subida» y «Bajada» a la vez 2 s: **1 movimiento**.

### 06.1.1 Programar el final de carrera de subida (p. 13)

Condición previa: Finales sin programar.

1. (motor) Llevar a la posición de subida (a pulsaciones).
2. (emisor programado) «Stop» y «Subida» a la vez 2 s: **2 movimientos y 3 pitidos**.

Primero el de subida: sin él no se puede programar el de bajada.

### 06.1.2 Programar el final de bajada (parada por presión) (p. 14)

Condición previa: Final de subida programado.

1. (emisor programado) Mantener «Bajada» 2 s.
2. (motor) Esperar a que haga el recorrido completo y pare por presión.

### 06.2 Borrar los finales de carrera (p. 14)

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «Bajada» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «P2» 1 s: **2 movimientos y 3 pitidos**.

Para modificar los finales (06.3) hay que modificar los dos: borrarlos y volver a programar 06.1.1 y 06.1.2.

### 07.1 Programar la parada intermedia (p. 16)

Condición previa: Finales de carrera programados.

1. (motor) Llevar el motor al punto deseado.
2. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «Stop» 1 s: **1 movimiento y 1 pitido**.
4. (emisor programado) «Stop» 1 s: **2 movimientos y 3 pitidos**.

### 07.2 Ir a la parada intermedia (p. 17)

Condición previa: Parada intermedia programada.

1. (emisor programado) Mantener «Stop» 2 s desde cualquier posición.

### 07.3 Borrar la parada intermedia (p. 17)

Condición previa: El motor en la parada intermedia.

1. (emisor programado) Ir a la parada intermedia («Stop» 2 s).
2. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «Stop» 1 s: **1 movimiento y 1 pitido**.
4. (emisor programado) «Stop» 1 s: **1 movimiento y 1 pitido**.

Es la misma botonera que programarla: cambia la respuesta final (1 movimiento y 1 pitido en vez de 2 y 3).

### 08.1 Copiar un emisor desde otro (p. 18)

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
3. (emisor nuevo) «P2» 1 s: **2 movimientos y 3 pitidos**.

### 08.2 Eliminar un emisor desde otro (p. 19)

Condición previa: Al menos 2 emisores programados.

1. (emisor que se mantiene) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor que se mantiene) «P2» 1 s: **1 movimiento y 1 pitido**.
3. (emisor que se elimina) «P2» 1 s: **2 movimientos y 3 pitidos**.

### 08.3 Eliminar todos los emisores (p. 20)

Condición previa: Un emisor programado.

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «Stop» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «P2» 1 s: **2 movimientos y 3 pitidos**.

### 08.4 Recuperar la memoria de un motor programado (p. 20)

Condición previa: Motor ya programado.

1. (motor) Quitar la corriente 5 s y volver a darla.
2. (emisor nuevo) «P2» 1 s: **1 movimiento**.
3. (emisor nuevo) «P2» 1 s: **1 movimiento**.
4. (emisor nuevo) «Subida» 1 s: **1 movimiento y 1 pitido**.

El manual dice «igual que el punto 04», pero las respuestas que da son otras (1 movimiento sin pitido en los dos «P2», y 1 y 1 al final).

### 09 Activar o desactivar hombre presente (p. 22)

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «Subida» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «Bajada» 1 s: **Activado: 1 movimiento y 1 pitido; desactivado: 2 movimientos y 3 pitidos**.

La misma botonera activa y desactiva: es un conmutador. La respuesta del último paso dice en qué modo queda.


## Esquemas e imágenes

- Las ilustraciones de los pasos son zonas renderizadas: `raw/gvt/motores_y_automatismos/elite/extraidos/manual_motor_elite_i_autotensado_es_gb_fr_it_de/imagenes/pNN_zonaK.png`. La de la p. 14 muestra la «parada del sistema por presión».
