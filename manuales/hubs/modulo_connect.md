# Módulo Connect. Manual de programación

Texto del manual de Gaviota «Módulo Connect» (12 páginas, solo en español, sin fecha ni versión). Original: `raw/gvt/motores_y_automatismos/hubs/manuales/Manual Módulo Connect.pdf`. Las imágenes citadas están en `raw/gvt/motores_y_automatismos/hubs/extraidos/manual_modulo_connect/`. Casi todo el manual son capturas de la app Gaviota con un texto debajo; aquí va el texto, en orden.

## 01 Descripción del producto

El Módulo Connect es un **controlador bidireccional WiFi a RF con interfaz RS485 integrada**. Se conecta al router WiFi de la vivienda y permite controlar persianas, toldos y screens con la app para teléfonos inteligentes, e interactuar con sistemas como Alexa Echo y Google Assistant a través de la API de la nube. La interfaz RS485 es una opción de integración en sistemas domóticos de terceros. (p. 3)

La app Gaviota permite controlar las persianas y toldos motorizados desde el teléfono. Para usarla hay que crear una cuenta, configurar el Módulo Connect y añadir las persianas y toldos. (p. 3)

Con la app y el Módulo Connect se puede (p. 3):
- controlar hasta **30 motores**;
- crear y controlar hasta **20 habitaciones**;
- crear y controlar hasta **20 escenarios**;
- crear y controlar hasta **20 temporizadores**.

## 02 Características

(p. 4; `imagenes/p04_img2.png`)

| Dato | Valor |
| --- | --- |
| Dimensiones | 75 × 132 × 35 mm (leídas del dibujo) |
| Alimentación | 5 V DC; 1000 mA |
| Emisión radio | RF 433 MHz |
| WiFi | 2,4 GHz |

## 03 Conexiones

El Módulo Connect se alimenta con el cable USB suministrado. (p. 4; `imagenes/p04_img3.png`: conector de alimentación en la base del módulo, junto a una toma tipo RJ y la rejilla del zumbador.)

## 04 Crear una cuenta

Primero hay que crear una cuenta con una dirección de correo y una contraseña (p. 5):
1. Introducir el correo y la contraseña, y pulsar «Crear cuenta».
2. Introducir y verificar de nuevo la contraseña, y pulsar «OK».
3. La cuenta queda creada; un mensaje de bienvenida indica que se puede seguir con la programación.

## 05 Añadir el Módulo Connect

Se vincula el Módulo Connect a la cuenta y a la app. El teléfono con el que se programa **tiene que estar conectado al WiFi de la vivienda**. (p. 6)
1. Pulsar «Añadir nuevo dispositivo».
2. Seleccionar «Puente».
3. Comprobar que el teléfono está conectado al WiFi y pulsar «OK».
4. Introducir la contraseña del WiFi y pulsar «Conectar».
5. Pulsar el botón del Módulo Connect hasta que el led parpadee en **color púrpura**, y pulsar «Siguiente».
6. La app muestra un vídeo explicativo:
   1. salir de la app Gaviota y entrar en los ajustes del teléfono;
   2. seleccionar la red WiFi que crea el Módulo Connect («conector…»);
   3. volver a la app Gaviota: empieza a buscar el módulo sola.
7. El Módulo Connect queda vinculado al WiFi. Pulsar «Siguiente». (p. 7)
8. Ponerle nombre al módulo y pulsar «OK». La app muestra el módulo vinculado. (p. 7)

## 06 Crear habitación

Para añadir motores hay que crear antes una habitación. (p. 8)
1. Pulsar «Añadir nueva habitación».
2. Ponerle nombre e imagen (una predeterminada o una foto hecha con el teléfono).
3. Pulsar «OK»: aparece «Añadido correctamente».

## 07 Añadir dispositivo y comprobar

Para añadir un motor se selecciona la habitación donde va. (p. 9)
1. Seleccionar la habitación y pulsar «+».
2. Seleccionar «Radio Motor».
3. Seleccionar el tipo de sistema (persiana, toldo, etc.) y pulsar «Añadir nuevo dispositivo».
4. Seleccionar el Módulo Connect en el que se quiere memorizar el motor (si hay varios) y pulsar «Siguiente».
5. Pulsar «Por control remoto». (La app explica: si ya se usa un mando, «Emparejar por control remoto»; si no, «Emparejar por motor». El manual solo describe la primera.)
6. La app indica cómo seguir según el motor sea Cross o Elite. En la captura (p. 9):
   - abrir la tapa trasera del emisor;
   - **gama Elite:** pulsar «P2» dos veces y a continuación pulsar «Siguiente»;
   - **gama Cross:** pulsar «Siguiente» y a continuación mantener «Stop» pulsado 3 segundos.
7. El Módulo Connect busca la señal del emisor (la app dice que puede tardar unos 30 segundos).
8. El Módulo Connect confirma que ha encontrado el dispositivo; pulsar «Siguiente».
9. Ponerle nombre e imagen al dispositivo y pulsar «OK». (p. 10)

**Comprobar el funcionamiento:** el motor aparece en la app. Desplazando el punto blanco se mueve el sistema a un porcentaje de su recorrido. (p. 10)

## 08 Escenario

En esta pestaña de la app se crean escenarios cuando hay varios dispositivos programados. Con una sola pulsación, un escenario puede, por ejemplo, subir del todo o a un porcentaje todas las persianas y a la vez bajar los toldos. Cada dispositivo puede tener una orden distinta: bajada, subida o un porcentaje de su recorrido. (p. 11)

## 09 Temporizador

En esta pestaña se crean temporizadores, que actúan sobre un dispositivo o sobre un escenario. Se pueden crear varios temporizadores para un mismo escenario o dispositivo. Cada dispositivo puede tener una orden distinta: bajada, subida o un porcentaje de su recorrido. (p. 11)
