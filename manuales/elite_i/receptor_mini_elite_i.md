# Receptor mini Elite-i. Manual de instalación

Texto en español del manual de Gaviota (sin versión), sacado de `raw/gvt/motores_y_automatismos/elite/manuales/Receptor Mini Elite Con Esquema.pdf`. Entre paréntesis, la página del PDF. Modelo: `receptor_mini_elite_i`.

Manual de una hoja, solo en español, sin referencia ni fecha.

## 1. Características técnicas (p. 1)

| | |
| --- | --- |
| Alimentación | 230 V AC, 50 Hz |
| Frecuencia | 433,925 MHz |
| Dimensiones | 4,8 × 4,6 × 2,3 cm |
| Motores | Hasta 50 Nm |

## 1. Funcionamiento (p. 1)

El receptor mini Elite convierte un motor mecánico en motor vía radio, para accionarlo con mando a distancia y con inversor pulsador. Con un módulo CONNECT de Gaviota, también se controla desde el móvil (iOS o Android) con la app Gaviota.

## 2. Notas preliminares (p. 1)

- Durante la configuración cada operación tiene que hacerse en menos de 10 s; si no, se cancela y vuelve al estado anterior.
- Una vez regulados los finales de carrera mecánicos y emparejado un emisor, hay que hacer **dos ciclos completos de subida y bajada** para que el receptor memorice las posiciones. Durante esos ciclos el motor no se debe parar, ni a mano ni por obstáculos. Hace falta para programar la parada intermedia, activar el modo impulsos y el hombre presente con pulsador, y usar la app Gaviota.
- El borne del interruptor o pulsador externo va con tensión.
- Símbolos: ↑↓ movimiento de subida y bajada; ☼ destello del led del receptor.

## 3. Conexiones (p. 2), de izquierda a derecha

| Borne | Conexión |
| --- | --- |
| 1 | Fase |
| 2 | Común del pulsador |
| 3 | Neutro |
| 4 | Neutro del motor |
| 5 | Subida del motor |
| 6 | Bajada del motor |
| 7 | Subida del pulsador |
| 8 | Bajada del pulsador |

## 13. Modos del pulsador o interruptor (p. 5)

| Modo | Cómo funciona | Respuesta al elegirlo |
| --- | --- | --- |
| 1. Pulsador doble (de fábrica) | «Subida» arranca hacia arriba; «Subida» o «Bajada» otra vez para. Igual con «Bajada» | 1 movimiento y 1 destello |
| 2. Interruptor | Se mueve mientras se mantiene «Subida» o «Bajada»; para al soltar | 2 y 2 |
| 3. Pulsador triple | «Subida», «Bajada» y «Stop» (el Stop alimenta las dos líneas a la vez). En modo impulso, más de 1 s seguido mueve de forma continua hasta «Stop» | 3 y 3 |
| 4. Pulsador simple | Un solo botón en cualquiera de las dos líneas: sube, para, baja, para | 4 y 4 |

## Procedimientos

Cómo responde el equipo: un **movimiento** (↑↓) es una subida y bajada corta del motor; un **destello** (☼) es un parpadeo del led del receptor. «P1» es el botón de configuración del receptor; «P2», el de la parte trasera del emisor.

### 4 Emparejar un emisor al dar corriente (método 1) (pp. 2 y 6)

Condición previa: Receptor recién alimentado.

1. (receptor) Dar corriente: **1 movimiento**.
2. (emisor nuevo) «Stop» 2 s (antes de 7 s): **2 movimientos y 3 destellos del led**.

### 4 Emparejar un emisor con el botón P1 (método 2) (p. 3)

1. (receptor) Mantener «P1» 2 s: **1 movimiento**.
2. (receptor) Soltar «P1»: **1 destello del led**.
3. (emisor nuevo) «Stop» 2 s: **2 movimientos y 3 destellos del led**.

En cualquier momento, sin cortar la corriente. Sirve también para añadir emisores.

### 5 Invertir el sentido de giro desde el emisor (p. 3)

1. (emisor programado) «Subida» y «Bajada» a la vez 2 s: **1 movimiento**.

### 5 Invertir el sentido de giro desde el receptor (método 2) (p. 3)

1. (receptor) Mantener «P1» unos 10 s: **3 movimientos durante ese tiempo**.
2. (receptor) Soltar «P1»: **3 destellos del led**.

### 6 Copiar un emisor (p. 3)

1. (emisor programado) «P2» de a: **1 movimiento y 1 destello del led**.
2. (emisor programado) «P2» de a: **1 movimiento y 1 destello del led**.
3. (emisor nuevo) «P2» de b: **2 movimientos y 3 destellos del led**.

La respuesta es con el led del receptor en vez de pitidos.

### 7 Programar la parada intermedia (p. 3)

Condición previa: Finales mecánicos regulados, un emisor emparejado y dos ciclos completos de subida y bajada sin parar.

1. (receptor) Llevar el motor a la posición deseada.
2. (emisor programado) «P2»: **1 movimiento y 1 destello del led**.
3. (emisor programado) «Stop»: **1 movimiento y 1 destello del led**.
4. (emisor programado) «Stop»: **2 movimientos y 3 destellos del led**.

### 7 Eliminar la parada intermedia (p. 4)

1. (emisor programado) «P2»: **1 movimiento y 1 destello del led**.
2. (emisor programado) «Stop»: **1 movimiento y 1 destello del led**.
3. (emisor programado) «Stop»: **1 movimiento y 1 destello del led**.

### 8 Eliminar los límites memorizados (p. 4)

1. (emisor programado) «P2»: **1 movimiento y 1 destello del led**.
2. (emisor programado) «Bajada»: **1 movimiento y 1 destello del led**.
3. (emisor programado) «P2»: **2 movimientos y 3 destellos del led**.

### 9 Eliminar un emisor (p. 4)

1. (emisor que se mantiene) «P2» de a: **1 movimiento y 1 destello del led**.
2. (emisor que se mantiene) «P2» de a: **1 movimiento y 1 destello del led**.
3. (emisor que se elimina) «P2» de b: **2 movimientos y 3 destellos del led**.

La respuesta es con el led del receptor en vez de pitidos.

### 10 Eliminar todos los emisores (p. 4)

1. (emisor programado) «P2»: **1 movimiento y 1 destello del led**.
2. (emisor programado) «Stop»: **1 movimiento y 1 destello del led**.
3. (emisor programado) «P2»: **2 movimientos y 3 destellos del led**.

### 11 Reset del receptor desde el botón (método 2) (p. 4)

1. (receptor) Mantener «P1» unos 14 s: **4 movimientos durante ese tiempo**.
2. (receptor) Soltar «P1»: **4 destellos del led**.

Método 1: eliminar todos los emisores (10) y eliminar los límites memorizados (8).

### 12 Modo impulsos o continuo (p. 4)

Condición previa: Posiciones superior e inferior memorizadas (dos ciclos completos).

1. (emisor programado) «P2»: **1 movimiento y 1 destello del led**.
2. (emisor programado) «Subida»: **1 movimiento y 1 destello del led**.
3. (emisor programado) «Bajada»: **Continuo: 2 movimientos y 3 destellos del led; impulsos: 1 movimiento y 1 destello del led**.

### 13 Modo del pulsador o interruptor externo (p. 5)

1. (emisor programado) «P2»: **1 movimiento y 1 destello del led**.
2. (emisor programado) «P2»: **1 movimiento y 1 destello del led**.
3. (emisor programado) «Stop», repetir la secuencia hasta la respuesta del modo: **Doble: 1 y 1; interruptor: 2 y 2; triple: 3 y 3; simple: 4 y 4 (movimientos y destellos)**.


## Esquemas e imágenes

- Esquema de conexiones: `raw/gvt/motores_y_automatismos/elite/extraidos/receptor_mini_elite_con_esquema/imagenes/p02_img1.png` (p. 2).
