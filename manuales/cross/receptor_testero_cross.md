# Receptor testero Cross: manual de instalación

Manual de Gaviota «Receptor testero Cross», versión «GAVIOTA · 07-18». Texto en español sacado de `raw/gvt/motores_y_automatismos/cross/manuales/Manual Inst - Receptor Testero Cross - ES_GB_FR_IT_DE_Actualizado_2019.pdf` (20 páginas, en español, inglés, francés, italiano y alemán). Entre paréntesis, la página del PDF. Las imágenes citadas están en `raw/gvt/motores_y_automatismos/cross/extraidos/manual_inst_receptor_testero_cross_es_gb_fr_it_de_actualizado_2019/`.

Modelo: `receptor_testero_cross` (hoja `modelos` del master de automatismos; artículo 60090153, 230 V). Producto descatalogado con soporte.

## Advertencias de seguridad (p. 2)

Leer detenidamente estas instrucciones de montaje antes de cualquier uso y conservarlas después de la instalación. No respetar las instrucciones de montaje, uso y especificaciones técnicas del artículo, o excederse en los rangos de uso máximos especificados (pesos, etc.), supone quedar fuera de la Política de Garantía y del Servicio Postventa de Gaviota Simbac, S.L.

## 1. Descripción del producto (p. 4)

El receptor testero Cross convierte un motor mecánico en un motor con funcionamiento vía radio, y además permite accionarlo desde un inversor pulsador. Se instala oculto en el testero y vale para cualquier tipo de motor mecánico. Puede accionar dos puntos de iluminación diferentes, por separado o juntos, desde el emisor. Es compatible con cualquier emisor de la gama Cross y trabaja con la central sol-viento y el sensor de movimiento Cross.

## 2. Características técnicas (p. 5)

| | |
| --- | --- |
| Alimentación | 230 V / 50 Hz |
| Frecuencia | 433,90 MHz |
| Potencia máxima | 400 W (motor GS-120) |
| Dimensiones | 108/121 × 36 × 22 mm |

Lleva un botón S2.

## 3. Emisores compatibles (p. 6)

- Emisor 1 canal Cross
- Emisor 15 canales Cross
- Emisor pared 1 canal Cross
- Emisor pared 15 canales Cross
- Reloj programador Cross
- Emisor llavero Cross
- Central sol viento Cross
- Sensor movimiento Cross

## 4. Esquema de conexionado (p. 7, `paginas/p07.png`)

| Hilo | Color | Función |
| --- | --- | --- |
| 1 | Amarillo-verde | Tierra |
| 2 | Azul | Neutro |
| 3 | Marrón | Subida o bajada |
| 4 | Negro | Subida o bajada |

El esquema muestra también el motor y el inversor pulsador (L).

## 5. Funciones de los puentes (jumpers) (p. 8)

| Modo | J2 | J3 |
| --- | --- | --- |
| Motor | desconectado | desconectado |
| Inversión de motor | desconectado | conectado |
| Iluminación | conectado | desconectado |
| Iluminación temporizada 30 s | conectado | conectado |

## 6. Funcionamiento (p. 9)

1. Con el receptor testero Cross un motor mecánico pasa a ser un motor vía radio, que se acciona con mando a distancia.
2. Los finales de carrera son los mecánicos del motor y se regulan desde su cabeza.
3. El motor se puede accionar por radio y con un inversor pulsador.
4. Puede accionar dos puntos de iluminación diferentes.

## 7. Programación (pp. 10-11)

**Paso 1. Corriente «ON».** Al dar corriente, responde con un pitido y un breve movimiento de subida y bajada: está alimentado.

**Paso 2.** Pulsar «P2» 2 veces (0,5 s cada vez) y después «Subida». Con un breve movimiento de subida y bajada indica que ha reconocido el emisor.

**Paso 3.** Si el sentido de giro no es el correcto, hay dos formas de invertirlo:
1. Desconectar la corriente 5 s, volver a conectar y empezar de nuevo pulsando «P2» 2 veces (0,5 s) y después «Bajada».
2. Conectar el puente J3 del receptor.

Atención (p. 11):
- Para funcionar con motor es imprescindible **no** tener puesto el puente J2.
- Los cortes de corriente se pueden hacer con una pulsación en el botón S2 del receptor.
- Desde que se alimenta el receptor o se hace un corte de corriente hay 10 segundos para entrar en programación.
- En modo motor, el tiempo máximo de funcionamiento es de 3 minutos. Pasado ese tiempo, el receptor deja de alimentar al motor.

## 8. Copia de emisores (p. 12)

**Paso 1.** Pulsar 2 veces el botón «P2» del emisor ya programado y después 1 vez el botón «P2» del emisor nuevo. Un breve movimiento de subida y bajada indica que el emisor nuevo ha quedado programado.

La central sol-viento funciona y se programa como un emisor.

## 9. Modalidades: hombre presente (p. 13)

El receptor tiene un funcionamiento de subida y bajada semiautomático, en el que el emisor actúa como un pulsador:
- Si se mantiene pulsado «Subida» o «Bajada» menos de 3 segundos, se para al soltar el botón.
- Si se mantiene pulsado «Subida» o «Bajada» más de 3 segundos, termina el recorrido solo.

**Paso 1.** Con el receptor alimentado, pulsar «P2», «Subida» y «P2». Un breve movimiento de subida y bajada indica el cambio de función.

Atención (p. 14): con el modo hombre presente desactivado, el emisor actúa como un interruptor: «Subida» y «Bajada» hacen la maniobra completa con una sola pulsación.

## 10. Modo iluminación (pp. 14-15)

En este modo, las dos salidas de motor del receptor son para dos puntos de luz diferentes:
- «Subida» enciende el primer punto de luz; otra pulsación lo apaga.
- «Stop» apaga cualquier punto de luz encendido.
- «Bajada» enciende el segundo punto de luz; otra pulsación lo apaga.

**Paso 1.** Con el puente J2 del receptor conectado, pulsar «P2» 2 veces (0,5 s) y después «Subida». Un breve movimiento de subida y bajada indica el cambio de función.

- Con J2 conectado (modo iluminación) no hay tiempo límite de funcionamiento.
- Con J2 y J3 conectados, el modo iluminación se apaga a los 30 segundos.

## 11. Borrado completo de la memoria (pp. 16-17)

Hay dos formas:
1. Pulsar 1 vez «P2» en el emisor, después «Stop» y por último «P2» otra vez. Un breve movimiento de subida y bajada indica que la memoria del receptor está borrada.
2. Mantener pulsado el botón S2 del receptor durante 10 segundos.

Atención (p. 17):
- Para borrar un emisor o una central sol-viento ya programados hay que hacer el borrado completo del receptor: no se pueden eliminar de uno en uno.
- Para volver a programar el receptor, empezar desde el paso 1 de la p. 10; hace falta un corte de corriente.
