# Protección de carga para USB
*(A.K.A USBcondom)*


**[Intro]**  
El bus USB (Universal Serial Bus) es un bus de comunicaciones utilizado como estándar de conexión de periféricos como: mouse, teclados, impresoras, cámaras de fotos y celulares, entre otros.  
El bus permite no solo la carga de un dispositivo sino también la transferencia de datos.  
  
**[Problemática]**  
El *juice jacking* es un tipo de ataque que consiste en el compromiso de una fuente de carga para luego atacar (sustraer info o comprometer) un dispositivo que sea conectado a dicha fuente de carga /energía.  
Este tipo de ataques suele darse en lugares públicos, como aeropuertos, estaciones de transporte público, plazas, donde suelen encontrarse estaciones de recarga para dispositivos móviles.  
  
**[Codificación de colores]**  
Este bus sigue una serie de definiciones con respecto a cables, protocolos y conectores.  
Conectores Tipo A y B  

| Color | Pin | Nombre | Descripción |
| ------ | ------ | ------ | ------ |
| Rojo/Naranja | 1 | Vcc | +5 |
| Blanco/Amarillo | 2 | D- | Data- |
| Verde | 3 | D+ | Data+ |
| Negro/Azul | 4 | GND | tierra |
  
**[Paso a paso]**  

   • Para esta prueba vamos a utilizar un simple cable prolongador.  
    <p align="center">
 <img src="https://github.com/cpeic/Educacion/blob/main/OAPTC/usbprot/img/1.jpeg" width="350" title="Cable USB" alt="Cable USB">
</p>
   • Procedemos a cortar el cable a una distancia de unos 10 cm del borde del conector.  
       <p align="center">
 <img src="https://github.com/cpeic/Educacion/blob/main/OAPTC/usbprot/img/2a.jpeg" width="350" title="Cable USB" alt="Cable USB">
</p>
   • A continuación podemos observar que el prolongador tiene una malla y luego los cables que identificamos anteriormente.  
          <p align="center">
 <img src="https://github.com/cpeic/Educacion/blob/main/OAPTC/usbprot/img/2c.jpeg" width="350" title="Cable USB" alt="Cable USB">
</p>  
   • Se deben volver a unir, solamente, los cables Rojo (Pin 1) y Negro (Pin 4)
             <p align="center">
 <img src="https://github.com/cpeic/Educacion/blob/main/OAPTC/usbprot/img/2b.jpeg" width="350" title="Cable USB" alt="Cable USB">
</p>  
     • Es posible utilizar termocontraible para proteger los empalmes realizados, una vez finalizado el dispositivo se encuentra listo para ser utilizado.
                  <p align="center">
 <img src="https://github.com/cpeic/Educacion/blob/main/OAPTC/usbprot/img/2.jpeg" width="350" title="Cable USB" alt="Cable USB">
</p>  
                  <p align="center">
 <img src="https://github.com/cpeic/Educacion/blob/main/OAPTC/usbprot/img/3.jpeg" width="350" title="Cable USB" alt="Cable USB">
</p>  
   
   
 *Nota:* Otra variante seria conectar los cables correspondientes a los pines 2 y 3 a un interruptor y en dispositivos confiables utilizar la transferencia de datos.  
 *Nota 2:* Con conectores USB para armar, es posible construir un filtro mucho más pequeño y portable que el prolongador.  
 
  
**[Referencias]**  
  • Krebs - Beware of juice jacking:  [krebsonsecurity.com](https://krebsonsecurity.com/2011/08/beware-of-juice-jacking/)  
  • USBCondom:  [usbcondom.org](https://usbcondom.org)  
  • USB Implementers Forum:  [usb.org](https://www.usb.org)  
  
