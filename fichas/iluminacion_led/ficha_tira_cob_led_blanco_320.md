# Ficha técnica: Tira COB LED blanco 320

Ficha técnica de Gaviota, de una página, sacada de `raw/gvt/motores_y_automatismos/iluminacion_led/fichas/SPA - FICHAS TECNICAS TIRAS/SPA - FICHA TECNICA TIRA COB LED BLANCO 320.pdf`. Los datos son los de la ficha, tal como vienen; al final, lo que no cuadra con el ERP o la tarifa.

![Dibujo de un tramo de tira LED COB (banda continua de luz amarilla con marcas de corte)](../../../raw/gvt/motores_y_automatismos/iluminacion_led/extraidos/ficha_80143557/imagenes/p01_img1.png)

## Especificaciones técnicas

| Característica | Valor |
| --- | --- |
| Descripción | Tira COB Led Blanco |
| Voltaje | 24 VDC |
| Consumo | 6 W/m |
| Temperatura | 3000 K |
| LED/m | 320 |
| Longitud tramo (distancia entre cortes) | 5 cm |
| Flujo luminoso | 480 lm/m |
| Protección | IP 67 (IP 65 en 80143557, 80143558, 80144072, como dice su nombre) |
| Tipo | COB |

## Referencias

| Referencia | Descripción | Longitud (m) | Conector |
| --- | --- | --- | --- |
| 80143557 | Tira Led COB 320L 6W 3000 5 IP65 L=5m | 5 | JST-RCY |
| 80143558 | Tira Led COB 320L 6W 3000 5 IP65 L=7m | 7 | JST-RCY |
| 80144072 | Tira Led COB 320L 6W 3000 5 IP65 L=9m | 9 | JST-RCY |
| 80144178 | Tira COB Led Blanco 320 L/m 6W 3000k 5 W/m L=5000 mm | 5 | STD |
| 80144179 | Tira COB Led Blanco 320 L/m 6W 3000k 5 W/m L=6000 mm | 6 | STD |

## Observaciones

Revisión de la ficha con el ERP (`raw/gvt/exports_articulos_ax/`) y la tarifa de iluminación Plug&Play 2025:

- Protección: la ficha dice IP 67, pero la descripción de 80143557, 80143558 y 80144072 (y su nombre en el ERP) dice IP65. Corregido en el texto y en la tabla: esos tres son IP65 (usuario, 2026-11-01: si el nombre dice otra IP, manda el nombre).
- Consumo: la ficha dice 6 W/m, pero 80144178 y 80144179 se llaman «… 5W/M» en el ERP y su descripción en la ficha dice a la vez «6W» y «5 W/m».
- Dos series con la misma tira: con conector JST-RCY (5, 7 y 9 m) y con conector STD (5 y 6 m). La ficha no dice qué cable o fuente va con cada una.
- El «5» que sigue a «3000» en las descripciones parece la longitud de tramo (5 cm), sin unidad.
