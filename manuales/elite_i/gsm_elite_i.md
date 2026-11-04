# Motor GSM Elite-i. Manual de instalación

Texto en español del manual de Gaviota (REF. 4004-0664, 06-20), sacado de `raw/gvt/motores_y_automatismos/elite/manuales/Manual Motor GSM Elite-i - ES_GB_FR_IT_DE.pdf`. Entre paréntesis, la página del PDF. Modelo: `gsm_elite_i`.

## Advertencias de seguridad (p. 2)

Leer las instrucciones antes de usar el producto y conservarlas. No respetar las instrucciones de montaje, uso y especificaciones, o exceder los rangos de uso (pesos, etc.), excluye el producto de la política de garantía y del servicio posventa de Gaviota Simbac.

## 01 Descripción del producto

El manual no tiene texto de descripción: pasa del índice a los emisores compatibles.

## Emisores compatibles (p. 4)

Emisor 1 canal Elite-i, emisor 15 canales Elite-i, emisor pared 1 canal Elite-i, emisor pared 15 canales Elite-i, sensor de movimiento Elite-i, módulo CONNECT, central sol viento Elite-i y central sol viento Elite-i inalámbrica.

## Conexiones (p. 5)

| Hilo | Color |
| --- | --- |
| 1 | Amarillo (amarillo-verde): tierra |
| 2 | Azul: neutro |
| 3 | Marrón: fase |

## Indicaciones previas a la programación (p. 6)

- Con varios motores, se programan alimentándolos de uno en uno.
- En los emisores de 15 canales el canal 0 es solo funcional: se deja libre de programaciones.

## 06.1 Programación de los finales de carrera (p. 9)

Los finales de carrera son mecánicos y se regulan con dos tornillos en la cabeza del motor:

- Las flechas «1» y «2» indican los dos sentidos de giro del tubo de enrollado.
- Al sentido «1» le corresponde el tornillo «A»; al sentido «2», el tornillo «B».
- Girando el tornillo hacia «+» el motor da más vueltas; hacia «−», menos.

Después hay que confirmarlos (06.2).

## 09 Borrado completo del motor (p. 15)

El manual dice que hay que hacer «los dos puntos siguientes», pero solo da uno: eliminar todos los emisores (07.3).

## Procedimientos

Cómo responde el equipo: un **movimiento** es un pequeño giro de subida y bajada del motor; un **pitido** es la señal sonora. «P2» es el botón de la parte trasera del emisor.

### 04 Asignar el primer emisor al motor (pp. 7-8)

Condición previa: Motor recién alimentado; con varios motores, alimentar uno cada vez.

1. (motor) Dar corriente: **Sin emisores: 1 movimiento y 1 pitido; con un emisor programado: 1 movimiento**.
2. (emisor nuevo) «Stop» 2 s: **2 movimientos y 3 pitidos**.

Distinto de los Elite-i: aquí basta con mantener «Stop» 2 s, sin «P2». Si el motor ya tenía emisor, conserva el sentido de giro y los emisores.

### 05 Invertir el sentido de giro (p. 8)

1. (emisor programado) «Subida» y «Bajada» a la vez 5 s: **1 movimiento**.

5 s, no 2 s como en los Elite-i. No hay condición de finales: son mecánicos.

### 06.2 Confirmar los finales de carrera (p. 10)

1. (motor) Regular los finales con los tornillos A y B (06.1).
2. (emisor programado) «Stop» y «Subida» a la vez 2 s: **1 movimiento; el motor hace solo un ciclo completo**.

### 07.1 Copiar un emisor desde otro (p. 11)

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
3. (emisor nuevo) «P2» 1 s: **2 movimientos y 3 pitidos**.

### 07.2 Eliminar un emisor desde otro (p. 12)

Condición previa: Al menos 2 emisores programados.

1. (emisor que se mantiene) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor que se mantiene) «P2» 1 s: **1 movimiento y 1 pitido**.
3. (emisor que se elimina) «P2» 1 s: **2 movimientos y 3 pitidos**.

### 07.3 Eliminar todos los emisores (p. 13)

Condición previa: Un emisor programado.

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «Stop» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «P2» 1 s: **2 movimientos y 3 pitidos**.

### 08 Activar o desactivar hombre presente (p. 14)

1. (emisor programado) «P2» 1 s: **1 movimiento y 1 pitido**.
2. (emisor programado) «Subida» 1 s: **1 movimiento y 1 pitido**.
3. (emisor programado) «Bajada» 1 s: **Activado: 1 movimiento y 1 pitido; desactivado: 2 movimientos y 3 pitidos**.

Conmutador, como en los Elite-i.


## Esquemas e imágenes

- Tornillos de los finales: `raw/gvt/motores_y_automatismos/elite/extraidos/manual_motor_gsm_elite_i_es_gb_fr_it_de/paginas/p09.png` (p. 9). Pasos: `paginas/` (pp. 8-14).
