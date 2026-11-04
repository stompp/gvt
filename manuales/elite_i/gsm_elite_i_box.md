# Motor GSM Elite-i Box. Manual de instalación

Texto en español del manual de Gaviota (REF. 4004-0666, 06-20), sacado de `raw/gvt/motores_y_automatismos/elite/manuales/Manual Motor GSM Elite-i Box - ES_GB_FR_IT_DE.pdf`. Entre paréntesis, la página del PDF. Modelo: `gsm_elite_i_box`.

## Advertencias de seguridad (p. 2)

Leer las instrucciones antes de usar el producto y conservarlas. No respetar las instrucciones de montaje, uso y especificaciones, o exceder los rangos de uso (pesos, etc.), excluye el producto de la política de garantía y del servicio posventa de Gaviota Simbac.

## 01 Descripción del producto (p. 4)

Los motores de la línea Elite-i Box llevan un final de carrera electrónico vía radio. Están diseñados para **toldos tipo cofre** y se controlan con emisores, sensores radio y la aplicación móvil. Los puntos de parada y el sentido de giro se programan con el emisor. Solo reciben señales de los emisores y sensores Elite-i de Gaviota.

Si se maniobra a mano desde el cáncamo o tras un corte de corriente, la primera maniobra que hace el motor es la subida.

## Emisores compatibles (p. 5)

Emisor 1 canal Elite-i, emisor 15 canales Elite-i, emisor pared 1 canal Elite-i, emisor pared 15 canales Elite-i, sensor de movimiento Elite-i, módulo CONNECT, central sol viento Elite-i y central sol viento Elite-i inalámbrica.

## Conexiones (p. 6)

| Hilo | Color |
| --- | --- |
| 1 | Amarillo (amarillo-verde): tierra |
| 2 | Azul: neutro |
| 3 | Marrón: fase |

## Indicaciones previas a la programación (p. 7)

- Si entre los pasos de la asignación de emisor pasan más de 10 segundos, hay que quitar la alimentación y empezar de nuevo.
- Con varios motores, se programan alimentándolos de uno en uno.
- En los emisores de 15 canales el canal 0 es solo funcional: se deja libre de programaciones.
- En todos los emisores el botón «P2» está en la parte trasera.
- Durante la programación de los finales de carrera el motor funciona a pulsaciones: hay que mantener 2 segundos el botón del sentido en el que se quiere mover. Si funciona de forma continua, los finales ya están programados.

## 06.3 Modificación de los finales de carrera (p. 15)

No se puede modificar un solo final de carrera: hay que modificar los dos. Para ello: borrar los finales (06.2), programar el de bajada (06.1.1) y programar el de subida (06.1.2).

## 10 Borrado completo del motor (p. 23)

Hay que hacer los dos puntos: borrar los finales de carrera (06.2) y eliminar todos los emisores (08.3). Si no se hace uno de ellos, se conserva su programación.

## Procedimientos

Cómo responde el equipo: un **movimiento** es un pequeño giro de subida y bajada del motor; un **pitido** es la señal sonora. «P2» es el botón de la parte trasera del emisor.

### 04 Asignar el primer emisor al motor (pp. 8-9)

Condición previa: Motor recién alimentado; menos de 10 s entre pasos; con varios motores, alimentar uno cada vez.

1. (motor) Dar corriente: **Sin emisores: 1 movimiento y 1 pitido; con un emisor programado: 1 movimiento**.
2. (emisor nuevo) «Stop» 2 s: **2 movimientos y 3 pitidos**.

Como en el GSM Elite-i: «Stop» 2 s, sin «P2». Si el motor ya tenía emisor, conserva su estado.

### 05 Invertir el sentido de giro (p. 10)

Condición previa: Sin finales de carrera programados.

1. (emisor programado) «Subida» y «Bajada» a la vez 2 s: **1 movimiento**.

### 06.1.1 Programar el final de carrera de bajada (p. 12)

Condición previa: Finales sin programar.

1. (motor) Llevar a la posición de bajada (a pulsaciones).
2. (emisor programado) «Stop» y «Bajada» a la vez 2 s: **2 movimientos y 3 pitidos**.

Primero el de bajada: sin él no se puede programar el de subida.

### 06.1.2 Programar el final de subida (cierre por presión) (p. 13)

Condición previa: Final de bajada programado.

1. (emisor programado) Mantener «Subida» 2 s.
2. (motor) Esperar a que haga el recorrido completo y cierre por presión.

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

### 08.4 Recuperar la memoria de un motor programado (p. 21)

Condición previa: Motor ya programado.

1. (emisor nuevo) «Stop» 2 s: **2 movimientos y 3 pitidos**.

El manual solo da este paso, sin cortar la corriente (en los Elite-i, cortar 5 s y P2, P2, Subida).

### 09 Activar o desactivar hombre presente (p. 22)

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «Subida» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «Bajada» 1 s: **Activado: 1 movimiento y 1 pitido; desactivado: 2 movimientos y 3 pitidos**.

La misma botonera activa y desactiva: es un conmutador. La respuesta del último paso dice en qué modo queda.


## Esquemas e imágenes

- Las ilustraciones de los pasos son zonas renderizadas: `raw/gvt/motores_y_automatismos/elite/extraidos/manual_motor_gsm_elite_i_box_es_gb_fr_it_de/imagenes/`.
