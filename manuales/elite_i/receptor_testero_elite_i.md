# Receptor testero Elite-i: manual de instalación

Manual de Gaviota, versión «GAVIOTA · 07-18». Texto en español sacado de `raw/gvt/motores_y_automatismos/elite/manuales/Manual Receptor Testero Elite - ES_GB_FR_IT_DE.pdf`. Entre paréntesis, la página del PDF. Las imágenes citadas están en `raw/gvt/motores_y_automatismos/elite/extraidos/manual_receptor_testero_elite_es_gb_fr_it_de/`.

Artículo: 60090175 Receptor testero Elite-i (230 V).

## Advertencias de seguridad (p. 2)

Leer detenidamente estas instrucciones de montaje antes de cualquier uso y conservarlas después de la instalación. No respetar las instrucciones de montaje, uso y especificaciones técnicas del artículo, o excederse en los rangos de uso máximos especificados (pesos, etc.), supone quedar fuera de la Política de Garantía y del Servicio Postventa de Gaviota Simbac, S.L.

## 1. Descripción del producto (p. 4)

El receptor testero Elite-i convierte un motor mecánico en un motor con funcionamiento vía radio, y además permite accionarlo desde un inversor pulsador. Se instala oculto en el testero y vale para cualquier tipo de motor mecánico. Puede accionar dos puntos de iluminación diferentes, por separado o juntos, desde el emisor. Es compatible con cualquier emisor de la gama Elite-i y trabaja con los automatismos Elite-i.

Atención: el receptor no debe mojarse ni manipularse con herramientas (pictogramas, `imagenes/p04_img1.png`).

## 2. Características técnicas (p. 5)

| | |
| --- | --- |
| Alimentación | 230 V / 50 Hz |
| Frecuencia | 433,90 MHz |
| Potencia máxima | 400 W (motor GS-120) |
| Dimensiones | 108/121 × 36 × 22 mm |

Lleva un botón S2 (dibujo con cotas: `imagenes/p05_img1.png`).

## 3. Emisores compatibles (p. 6)

- Emisor 1 canal Elite-i
- Emisor 15 canales Elite-i
- Módulo CONNECT
- Emisor pared 1 canal Elite-i
- Emisor pared 15 canales Elite-i
- Sensor movimiento Elite-i
- Central sol viento Elite-i
- Central sol viento Elite-i inalámbrica

## 4. Esquema de conexionado (p. 7)

Esquema: `imagenes/p07_zona1.png` (receptor, inversor pulsador y cables) y `imagenes/p07_zona2.png` (cabeza del motor).

1. Amarillo-verde: tierra
2. Azul: neutro
3. Marrón: subida o bajada
4. Negro: subida o bajada

### Funciones de los puentes (jumpers) (p. 8)

Foto del receptor abierto: `imagenes/p08_img4.png`.

| Modo | J2 | J3 |
| --- | --- | --- |
| Motor | desconectado | desconectado |
| Inversión de motor | desconectado | conectado |
| Iluminación | conectado | desconectado |
| Iluminación temporizada 30 s | conectado | conectado |

## 5. Funcionamiento (p. 9)

- Con el receptor testero Elite-i un motor mecánico pasa a ser vía radio, para accionarlo con mando a distancia.
- Los finales de carrera son mecánicos y se regulan desde la cabeza del motor.
- Se puede accionar vía radio y con inversor pulsador.
- Puede accionar dos puntos de iluminación diferentes.

## 6. Programación (pp. 10-11)

Los pasos están en [receptor_testero_elite_i_procedimientos.md](receptor_testero_elite_i_procedimientos.md).

Atención (p. 11):
- Para funcionar con motor es imprescindible **no** tener puesto el J2.
- Los cortes de corriente se pueden hacer con una pulsación en el botón S2 del receptor.
- Desde que se da corriente al receptor o se hace un corte de corriente hay 10 segundos para entrar en programación.
- En modo motor el tiempo de funcionamiento máximo es de 3 minutos: pasado ese tiempo, el receptor deja de alimentar al motor.

## 7. Copia de emisores (pp. 12-13)

Copiar un emisor desde otro y eliminar un emisor desde otro: ver los procedimientos. Para eliminar un emisor desde otro tiene que haber al menos 2 emisores programados.

## 8. Hombre presente (pp. 13-15)

Con hombre presente, para mover el motor hay que mantener pulsado el botón del sentido de giro («Subida» o «Bajada») durante 2 segundos, lo que protege de accionamientos no intencionados. Con hombre presente desactivado, el emisor actúa como un interruptor: una sola pulsación de «Subida» o «Bajada» hace la maniobra completa.

## 9. Borrado completo del receptor (p. 15)

Ver los procedimientos.

## 10. Modo iluminación (p. 16)

Las salidas de conexión del motor pasan a ser dos puntos de luz diferentes:
- «Subida» enciende el primer punto de luz; otra pulsación lo apaga.
- «Bajada» enciende el segundo punto de luz; otra pulsación lo apaga.
- «Stop» apaga cualquier punto de luz encendido.

Con J2 conectado (modo iluminación) no hay tiempo límite. Con J2 y J3 conectados, el modo iluminación se apaga a los 30 segundos.
