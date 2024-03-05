# VNC 
Virtual Networking Computing. Programa de software *libre* que se basa en  una estructura cliente-servidor, este permite observar las acciones del ordenador *servidor* remotamente a través de un cliente.[1]  
## Funcionamiento
Se compone de cliente, servidor y un **protocolo de comunicación**
- El *servidor* es el programa del equip que comparte su pantalla. Y de forma pasiva permite al cliente tomar control.  
- El *cliente* es el programa que vigila, controla e interactúa con el servidor. Este controla al servidor.  
- El *protocolo* (RFB), se basa de una primitiva gráfica del servidor "Put a rectangle of pixel data at the specified X,  position" y maneja mensajes de eventos desde el cliente al servidor.  
El protocolo VNC permite que el cliente y el servidor negocien la codificación,  como la (raw), donde los datos se enviían e píxeles por scanline, VNC utiliza el puerto TCP por defecto 5900+N, donde N es el número de la pantalla. 



# Referencias
[1]  C. de, “VNC,” _Wikipedia.org_, Apr. 12, 2005. https://es.wikipedia.org/wiki/VNC (accessed Mar. 05, 2024).

‌