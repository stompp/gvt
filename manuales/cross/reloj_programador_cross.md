# Reloj programador Cross: manual de instalación

Manual de Gaviota «Reloj programador Cross», versión «REF. 6009-140 · GAVIOTA · 11-17». Texto en español sacado de `raw/gvt/motores_y_automatismos/cross/manuales/Manual Instalacion - Reloj Programador Cross.pdf` (14 páginas, en español, inglés, francés, italiano y portugués). Entre paréntesis, la página del PDF. Las imágenes citadas están en `raw/gvt/motores_y_automatismos/cross/extraidos/manual_instalacion_reloj_programador_cross/`.

Modelo: `reloj_programador_cross` (hoja `modelos` del master de automatismos; artículo 60090140, reloj programador de pared). Producto descatalogado con soporte.

## Advertencias de seguridad (p. 3)

Leer detenidamente estas instrucciones de montaje antes de cualquier uso y conservarlas después de la instalación. No respetar las instrucciones de montaje, uso y especificaciones técnicas del artículo, o excederse en los rangos de uso máximos especificados (pesos, etc.), supone quedar fuera de la Política de Garantía y del Servicio Postventa de Gaviota Simbac, S.L.

## 1. Datos técnicos (p. 5)

| | |
| --- | --- |
| Alimentación | Pila CR2430 (3 V) |
| Temperatura de trabajo | de −20 °C a +50 °C |
| Frecuencia de trabajo | 433,90 MHz |

El reloj controla automáticamente, vía radio, motores Cross, Cross Box, Radio GSM y receptores de la serie Cross según la programación horaria. Está pensado sobre todo para persianas.

El reloj activa un receptor igual que cualquier otro emisor Cross, pero sus órdenes no las da una persona: las genera la programación horaria.

Capacidad:
- Cada reloj programador Cross puede accionar un número ilimitado de receptores.
- En un motor o receptor solo se puede memorizar 1 reloj programador Cross (1 código).

## 2. Función de los controles (p. 6, `imagenes/p06_img1.png`)

| Botón | Posición | Para qué |
| --- | --- | --- |
| A. «+» | izquierda, arriba | Poner en hora y programar las horas en modo automático |
| B. «o» | izquierda, centro | Cambiar el modo de funcionamiento (MAN, AUTO y AUTO aleatorio) |
| C. «−» | izquierda, abajo | Poner en hora y programar las horas en modo automático |
| D. «▲» (subida) | derecha, arriba | Subida manual del motor |
| E. «−» (stop) | derecha, centro | Para el motor si está haciendo una maniobra |
| F. «▼» (bajada) | derecha, abajo | Bajada manual del motor |

## 3. Modos de funcionamiento (p. 8)

- **Manual (MAN):** la programación horaria está desactivada; el motor se mueve con los botones de subida, stop y bajada.
- **Automático (AUTO):** el motor sube y baja solo a las horas programadas; también se puede mover a mano.
- **Automático aleatorio (AUTO con un símbolo sobre «UT»):** igual que AUTO y con la misma programación, pero la hora de subida y de bajada es aleatoria, con un margen de hasta 30 minutos desde la hora programada.

Se cambia de modo en cualquier momento manteniendo pulsado «o» hasta llegar al modo deseado.

## 4. Puesta en hora y día de la semana (p. 9)

1. Mantener pulsado «o» hasta llegar al modo MAN (debajo de la hora y los minutos).
2. Mantener pulsado «+» hasta que parpadeen los dígitos de las horas (HOURS).
3. Con pulsaciones de «+» se pasa de la hora a los minutos y, arriba, a los días de la semana.
4. Con SUBIDA y BAJADA se cambia la hora, los minutos o el día de la semana, según dónde se esté.
5. Al terminar, mantener pulsado «−» hasta que parpadeen a la vez las horas y los minutos (HOURS y MINUTES).

En cualquier momento se puede salir pulsando STOP; entonces no se guarda ningún cambio.

## 5. Programación de la subida y la bajada automáticas (p. 10)

1. Mantener pulsado «o» hasta llegar al modo AUTO (debajo de la hora y los minutos).
2. Mantener pulsado «+»: lleva a la programación del domingo (SU).
   - Aquí se puede revisar lo programado con BAJADA y SUBIDA, para avanzar o retroceder entre los días de la semana y las subidas y bajadas programadas.
3. Pulsar «+» para empezar a programar: el dígito de la hora parpadea.
   - Con «−» se cambia de día de la semana.
   - Con «o» se cambia entre la programación de la subida y la de la bajada.
   - Con «+» se cambia entre la hora y los minutos.
4. En la posición que se quiere cambiar, ajustar con SUBIDA y BAJADA.
5. Al terminar todos los días de la semana, mantener pulsado «−» hasta que parpadeen a la vez las horas y los minutos.

Además:
- Hay que programar los días de la semana uno a uno: no se puede hacer una sola programación para todos los días.
- Entre la subida y la bajada de un mismo día tiene que haber al menos 32 minutos; con 31 da error (ER01). Por ejemplo, con la subida a las 08:00, la bajada tiene que ser a partir de las 08:32.
- En los modos AUTO y «AUTO» (el manual lo llama aquí «Hombre presente»), cada orden de subida o bajada hace el recorrido completo: no se puede programar la parada intermedia.

## Lo que no está en el manual

El manual no explica cómo se programa el reloj en un motor o receptor. Según el usuario (usuario, 2026-10-31): el reloj es un mando Cross con funciones de programación horaria y los mismos botones que el emisor de pared de 15 canales. Se programa como un emisor más: «P2» 2 veces en un emisor ya programado y, en el reloj, «o» y «+» a la vez (no tiene botón «P2»).
