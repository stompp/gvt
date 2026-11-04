# Central sol-viento Cross: manual de instalación

Manual de Gaviota «Central sol viento Cross», versión «REF. 6009-141 · GAVIOTA · 07-18». Texto en español sacado de `raw/gvt/motores_y_automatismos/cross/manuales/Manual Inst - Central Sol_Viento Cross - ES_GB_FR_IT_DE_Actualizado_2019....pdf` (12 páginas, en español, inglés, francés, italiano y alemán). Entre paréntesis, la página del PDF. Las imágenes citadas están en `raw/gvt/motores_y_automatismos/cross/extraidos/manual_inst_central_sol_viento_cross_es_gb_fr_it_de_actualizado_2019/`.

Modelo: `central_sv_cross` (hoja `modelos` del master de automatismos; artículo 60090141). Sigue a la venta (master de automatismos, duda 9), aunque sea del sistema Cross.

## Advertencias de seguridad (p. 2)

Leer detenidamente estas instrucciones de montaje antes de cualquier uso y conservarlas después de la instalación. No respetar las instrucciones de montaje, uso y especificaciones técnicas del artículo, o excederse en los rangos de uso máximos especificados (pesos, etc.), supone quedar fuera de la Política de Garantía y del Servicio Postventa de Gaviota Simbac, S.L.

## 1. Datos técnicos (p. 4)

| | |
| --- | --- |
| Alimentación | 220 V 50 Hz |
| Índice de protección | IP34 |
| Temperatura de trabajo | de −20 °C a +50 °C |
| Frecuencia de trabajo | 433,90 MHz |
| Umbral de velocidad del viento | de 10 a 50 km/h |
| Umbral de intensidad de luz solar | de 10 a 60 klux |

La central controla automáticamente, vía radio, motores Cross, Cross Box, Radio GSM y receptores de la serie Cross, según las condiciones de sol y viento. Está pensada sobre todo para toldos.

La central activa un receptor igual que cualquier otro emisor Cross, pero sus órdenes no las da una persona: las genera el sensor sol-viento cuando detecta cambios en el tiempo.

Capacidad:
- Cada central sol-viento Cross puede accionar un número ilimitado de receptores.
- En un motor o receptor solo se puede memorizar 1 central sol-viento Cross (1 código).

## 2. Emisores compatibles (p. 6)

- Emisor 1 canal Cross
- Emisor 15 canales Cross
- Emisor pared 1 canal Cross
- Emisor pared 15 canales Cross

## 3. Función de los controles y conexionado (p. 7, `imagenes/p07_zona1.png`)

- **A.** Ajuste del umbral de velocidad del viento, de 10 a 50 km/h.
- **B.** Ajuste del umbral de intensidad de luz solar, de 10 a 60 klux.
- **C.** Botón UP: recoge el toldo programado con la central.
- **D.** Botón P2: para programar la central.
- **E.** Indicador luminoso: parpadea al detectar alimentación y al enviar una señal al motor.

Conexionado:

| Hilo | Color | Función |
| --- | --- | --- |
| 1 | Azul | Neutro |
| 2 | Marrón | Fase |

## 4. Modos de funcionamiento (p. 8)

- **Modo manual:** la central manda la orden de recogida cuando se supera la velocidad de viento fijada. El toldo se extiende a mano, desde el emisor.
- **Modo automático:** la central manda la orden de bajada cuando la luz del sol supera el umbral de luminosidad, y la de recogida cuando el viento supera la velocidad fijada o baja la intensidad del sol.

## 5. Regulación de los sensores de sol y viento (p. 8)

| Posición | Sol | | Posición | Viento |
| --- | --- | --- | --- | --- |
| 0 | Anulado | | 0 / 1 | 10 km/h |
| 1 | 15 klux | | 1 | 15 km/h |
| 2 | 30 klux | | 2 | 30 km/h |
| 3 | 45 klux | | 3 | 50 km/h |
| 4 | 60 klux | | | |

La tabla del viento da 10 km/h para «0 / 1» y 15 km/h para «1»: está así en el manual.

## 6. Programación de la central (p. 9)

Con el motor ya programado:
1. Pulsar 2 veces el botón P2 del emisor programado.
2. Pulsar 1 vez el botón P2 de la central sol-viento.
3. El motor hace un movimiento de subida y bajada: la central queda programada.

## 7. Activación del modo de funcionamiento (p. 9)

Desde el emisor:
- **Modo manual:** pulsar a la vez «Stop» y «Bajada». El motor hace 1 movimiento de subida y bajada: ha reconocido el cambio.
- **Modo automático:** pulsar a la vez «Stop» y «Subida». El motor hace 3 movimientos de subida y bajada: ha reconocido el cambio.

Además:
- En los emisores de 15 canales, con el modo automático activado aparece un sol arriba a la izquierda de la pantalla.
- Si la central maneja varios motores, el modo manual o automático se puede activar en cada uno por separado, desde su emisor.
- Con un emisor de 15 canales se puede cambiar el modo de todos los motores a la vez desde el canal 0.

## 8. Tiempo de activación de las funciones (p. 11)

| Tiempo | Qué hace |
| --- | --- |
| 5 minutos | Desde que se supera el umbral de luz fijado hasta que manda la orden de bajada |
| 15 minutos | Desde que la luz no llega al umbral fijado hasta que manda la orden de recogida |
| 5 segundos | Desde que se supera la velocidad de viento fijada hasta que manda la orden de recogida |
| 8 minutos | Tras una recogida por viento, hasta que el toldo vuelve a funcionar |
