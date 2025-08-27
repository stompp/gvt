FUNCIONAMIENTO MOTORES ELITE-I

# Contenido Del Documento

En este documento se describe el funcionamiento de los motores de la gama Elite/Elite-i.

Se tratan de motores tubulares utilizados en sistemas como persianas, toldos, cerramientos verticales, screens, cortavientos, toldos planos como palilleras o pérgolas o similares.

Tipos de motor dentro de la gama:

Normal : En los motores normales deben programarse ambos  finales de carrera.

Box: Se utilizan en sistemas tipo cofre en los que se debe programar manualmente el final de carrera de bajada/salida y el de subida/cierre se realiza automáticamente por presión.

Autotensado: Se utilizan en sistemas tipo zen, zen rain  en los que se debe programar manualmente el final de carrera de subida/cierre y el de bajada/salida se realiza automáticamente por tensión al estirar. Un sinónimo es "rain".

Incluye comportamiento, funciones y como realizarlas al introducir comandos con el mando. Se describen las diferentes secuencias y combinaciones de botones a pulsar en el mando para realizar las diferentes funciones de las que dispone el motor.

# Símbolos

[MOV] = Significa que el motor hace un movimiento de subida y bajada o vaivén.

[BIP] = Significa que el motor emite un pitido/bip.

Los comandos de programación son secuencias de tres botones pulsados de uno en uno que empiezan siempre al pulsar el botón P2.

# Notas Básicas Sobre Los Mandos

Para poder controlar los motores los mandos disponen de al menos los siguientes botones:

P2 = Botón utilizado para la programación del motor. Todos Los comandos de programación comienzan pulsando este botón.

Subida  = Al pulsar este botón el motor siempre deberá subir. En un toldo lo cerraría o recogería. En persianas debe abrirlas al subirlas. Puedo ser parte de un comando de programación o pulsarse junto a otro botón en combinación.

Stop = Al pulsar este botón el motor debería parar si está en movimiento. . Puedo ser parte de un comando de programación o pulsarse junto a otro botón en combinación.

Bajada = Al pulsar este botón el motor siempre deberá bajar. En un toldo lo abriría/extendería. En persianas debe cerrarlas al bajarlas. Puedo ser parte de un comando de programación o pulsarse junto a otro botón en combinación.

En caso de que un mando no conste de botón P2, tan solo podrá controlar el movimiento del motor o enlazar con este.

Ejemplo de comando

P2 ([MOV] y [BIP]) - Stop ([MOV] y [BIP]) - Subida ([MOV][MOV] y [BIP][BIP][BIP]).  Significa que primero pulsemos P2 y el motor responde con movimiento y pitido, luego pulsemos  Stop y el motor responde con movimiento y pitido y finalmente pulsemos  Subida y el motor responde con doble movimiento y triple pitido.

# Funcionamiento De Los Motores Elite

¿Qué ocurre al alimentar el motor?

Al alimentarlo, el motor puede responder de dos modos:

[MOV] y [BIP]. Indica que el motor se ha iniciado y no hay emisor programado en la memoria.

[MOV]. Indica que el motor tiene al menos un emisor programado.

Tras alimentarlo el motor estará a la escucha en modo enlace durante 10 segundos. Durante este tiempo el motor estará a la espera de una secuencia de enlace de un mando.

Si durante este tiempo se pulsa alguna tecla de algún emisor ya memorizado, el motor saldrá del modo enlace según

Si el motor no tiene ambos finales de carrera memorizados se moverá paso a paso debiendo mantener pulsado subida o bajada para que mueva continuo.

¿Cómo asignar/enlazar un mando al motor? = ASIGNAR UN EMISOR

Podrá realizarse mientras el motor esté en modo enlace.  Si transcurren más de 10 segundos desde el encendido del motor y la asignación del emisor, será necesario quitar la alimentación y comenzar de nuevo.

Para asignar un emisor al motor tenemos tres opciones:

Pulsar P2 ([MOV] y [BIP]) - P2 ([MOV] y [BIP]) - Subida ([MOV][MOV] y [BIP][BIP][BIP]).  Si el motor no tiene ningún emisor programado también se definirá el sentido de giro como sentido horario/dextrógiro.

Pulsar P2 ([MOV] y [BIP]) - P2 ([MOV] y [BIP]) - Bajada ([MOV][MOV] y [BIP][BIP][BIP]).  Si el motor no tiene ningún emisor programado también se definirá el sentido de giro como sentido antihorario/levógiro.

Mantener pulsado el botón de STOP durante 3-5 segundos hasta obtener la respuesta de confirmación [MOV][MOV] y [BIP][BIP][BIP]. Es equivalente a pulsar P2-P2-Subida.

¿Cómo invertir el sentido de giro? = INVERTIR EL SENTIDO DE GIRO

Si el sentido de giro no es el correcto, debe modificarse previamente antes de establecer los finales de carrera. Si al menos un final de carrera está definido habrá que eliminar los finales de carrera para poder invertir el sentido de giro.

Para invertir el sentido de giro hay que mantener pulsado Subida y Bajada durante 3-5 segundos hasta obtener la respuesta ([MOV])

¿Cómo defino los finales de carrera? = DEFINIR FINALES DE CARRERA

NOTA: Si los finales de carrera no han sido memorizados el movimiento del motor será a impulsos. Para un movimiento continuo deberemos dejar presionado el botón del sentido en el que deseemos desplazar el motor durante 2 segundos. Si el movimiento del motor es continuo significa que los finales de carrera ya están programados.

## 4.1 Motor Eli

# Final De Carrera De Bajada

Llevar hasta la posición deseada y entonces

Stop + Bajada 2s. ([MOV][MOV] y [BIP][BIP][BIP])

En motores Elite-i Autotensado se establece automáticamente por tensión.

# Final De Carrera De Subida

Llevar hasta la posición deseada y entonces

Stop + Subida 2s. ([MOV][MOV] y [BIP][BIP][BIP])

En motores Elite-i Box se establece automáticamente al cerrar por presión.

# Modificar Finales De Carrera

Para modificar un final de carrera deben haber sido memorizados ambos previamente. Solo es posible modificarlos por separado en motores normales, en motores Box  y Autotensado habrá que realizar el comando descrito en BORRAR FINALES DE CARRERA

# Borrar Final De Carrera De Bajada

Solo en motores normales. Llevar hasta la posición deseada y entonces:

Stop + Bajada 5s. ([MOV] y [BIP])

# Borrar Final De Carrera De Subida

Solo en motores normales. Llevar hasta la posición deseada y entonces:

Llevar hasta la posición deseada y entonces

Stop + Subida 5s. ([MOV] y [BIP])

Llevar a la nueva posición deseada y repetir el proceso ya descrito en FINALES DE CARRERA.

# Borrar Finales De Carrera

P2 ([MOV] y [BIP]) - Bajada ([MOV] y [BIP]) – P2 ([MOV][MOV] y [BIP][BIP][BIP])

# Parada Intermedia

P2 ([MOV] y [BIP]) - Stop ([MOV] y [BIP]) – Stop ([MOV][MOV] y [BIP][BIP][BIP])

# Borrar Parada Intermedia

P2 ([MOV] y [BIP]) - Stop ([MOV] y [BIP]) – Stop ([MOV] y [BIP])

# Buscar Parada Intermedia

Stop 2s

# Copiar Emisor

Siendo a un emisor ya programado y b el emisor a añadir.

P2a ([MOV] y [BIP]) - P2a ([MOV] y [BIP]) – P2b ([MOV][MOV] y [BIP][BIP][BIP])

# Eliminar Emisor

Siendo a el emisor a mantener y b el emisor a eliminar.

P2a ([MOV] y [BIP]) - P2a ([MOV] y [BIP]) – P2b ([MOV][MOV] y [BIP][BIP][BIP])

# Eliminar Todos Los Emisores

P2 ([MOV] y [BIP]) - Stop ([MOV] y [BIP]) – P2 ([MOV][MOV] y [BIP][BIP][BIP])

# Activar Modo Impulsos

P2 ([MOV] y [BIP]) - Subida ([MOV] y [BIP]) – Bajada ([MOV] y [BIP])

# Desactivar Modo Impulsos

P2 ([MOV] y [BIP]) - Subida ([MOV] y [BIP]) – Bajada ([MOV][MOV] y [BIP][BIP][BIP])

Solo Elite-i Box

# Desactivar Tensado Inferior

P2 ([MOV] y [BIP]) - Stop ([MOV] y [BIP]) – Bajada ([MOV] y [BIP])

# Activar Tensado Inferior

P2 ([MOV] y [BIP]) - Stop ([MOV] y [BIP]) – Bajada ([MOV][MOV] y [BIP][BIP][BIP])

Central Sol y Viento

# Enlazar Central

Siendo a un emisor ya programado y b la central a enlazar.

P2a ([MOV] y [BIP]) - P2a ([MOV] y [BIP]) – P2b ([MOV][MOV] y [BIP][BIP][BIP])

# Eliminar Central

Siendo a un emisor ya programado y b la central enlazada a eliminar.

P2a ([MOV] y [BIP]) - P2a ([MOV] y [BIP]) – P2b ([MOV][MOV] y [BIP][BIP][BIP])

# Activar Modo Sol Automático

Subida + Bajada – Subida ([MOV][MOV] y [BIP][BIP][BIP])

# Desactivar Modo Sol Automático

Subida + Bajada – Bajada ([MOV] y [BIP])

Sensor de Movimiento

# Enlazar Sensor

Siendo a un emisor ya programado y b el sensor a enlazar. Con el potenciómetro S2 en posición 0.

P2a ([MOV] y [BIP]) - P2a ([MOV] y [BIP]) – S1b ([MOV][MOV] y [BIP][BIP][BIP])

# Eliminar Sensor

Siendo a un emisor ya programado y b el sensor a eliminar. Con el potenciómetro S2 en posición 0.

P2a ([MOV] y [BIP]) - P2a ([MOV] y [BIP]) – S1b ([MOV][MOV] y [BIP][BIP][BIP])