# SolarSwitch

SolarSwitch es en esencia un programador astronómico desarrollado de forma modular y en base a un microcontrolador como principal elemento de control. Es por tanto un sistema flexible, fácilmente ampliable y dinámico, que se adapta a múltiples situaciones.

Entre las ventajas que incorpora podemos destacar:

Si se combina con el firmware SolarSwitch-Core, podemos destacar las siguiente ventajas: 
* Funcionamiento de forma independiente. No es necesario la conexión a redes de 
datos. Otros dispositivos se bloquean o dejan de realizar su función si no están 
conectados a la red internet.  
* No le afectan los cortes de suministro eléctrico. Cuando el servicio se restablece 
SolarSwitch-Core retoma la programación en el punto en el que debería estar como si 
no hubiera habido corte alguno. Algunos dispositivos se tienen que volver a 
programar y poner en hora después de una falta de suministro eléctrico. Los que 
no les afecta los cortes tienen un tiempo limitado de ‘memoria’. SolarSwitch-Core pude 
estar más de 8 años sin suministro (sustituyendo la pila del modulo RTC DS3231 por un
portapilas de 2xAAA), cuando se restablezca será como si no hubiera 
pasado nada. Seguirá funcionando como debe. 
* Puede funcionar tanto en la red eléctrica como de forma aislada, 
autoabasteciéndose con paneles solares, lo que facilita la instalación en lugares 
sin acometida eléctrica. (Para ello es necesario el modelo DC y la instalación del 
dispositivo ‘SolarBank’) 
* No le afecta el cambio de horario verano/invierno. Se ajusta automáticamente al 
cambio horario y a la zona horaria. Puede utilizarse en cualquier parte. 
* Programación sencilla desde un navegador web. Sin complicadas aplicaciones. 
Sin cables. Sin conocimientos de programación. Permite hasta 3 horarios 
programables por circuito.
* API documentada que facilita la adopción de soluciones de terceros para la gestión.
* Pensado para que funcione ‘toda la vida’. ¿Qué queremos decir? Que no tiene 
‘obsolescencia’. SolarSwitch-Core cuidadosamente programadao y testado para llegar hasta 
el 31 de diciembre de 2.159. Más allá del límite del propio hardware.

Ya no sólo en la iluminación, si observamos el porcentage del gasto energético en 
calefacción y agua caliente, un ahorro en cualquiera de éstas áreas supone un gran 
ahorro de la factura.  
