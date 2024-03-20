# VNC Virtual Networck Computing
Virtual Networking Computing. Programa de software *libre* que se basa en  una estructura cliente-servidor, este permite observar las acciones del ordenador *servidor* remotamente a través de un cliente.[1]  
## Funcionamiento
Se compone de cliente, servidor y un **protocolo de comunicación**
- El *servidor* es el programa del equip que comparte su pantalla. Y de forma pasiva permite al cliente tomar control.  
- El *cliente* es el programa que vigila, controla e interactúa con el servidor. Este controla al servidor.  
- El *protocolo* (RFB), se basa de una primitiva gráfica del servidor "Put a rectangle of pixel data at the specified X,  position" y maneja mensajes de eventos desde el cliente al servidor.  
El protocolo VNC permite que el cliente y el servidor negocien la codificación,  como la (raw), donde los datos se enviían e píxeles por scanline, VNC utiliza el puerto TCP por defecto 5900+N, donde N es el número de la pantalla. 

# SPICE virtual viewer
Simple Protocol for Independent Computing Environments es un protocolo de comunicación para entornos virtuales, permite a los usuarios ver la consola virtual de las VM desde cualquier lado via internet.[2]

# Team Viewer
Es un software de acceso remoto, que permite controlar de forma remota a los usuarios y controlar de manera remota dispositivos como computadoras, teléfonos, tabletas, etc. Utiliza tecnología de escritorio remoto para establecer una conexión segura entre los dispositivos. Lo que permite a los usuarios ver la pantalla del dispositivo remoto, controlar el mouse y el teclado y transferir archivos entre los dispositivos conectados.

# Any Desk
Es un software de escritorio remoto que permite a los usuarios acceder y controlar de forma remota dispositivos como computadoras y dispositivos móviles a través de Internet. Any Desk se destaca por su rapidez y baja latencia en la transmisión de datos, lo que proporciona una experiencia fluida y receptiva incluso en conexiones de Internet lentas.
# Diferencias y similitudes
1. Protocolo de comunicación:
    
    - VNC y SPICE son protocolos de comunicación específicamente diseñados para acceso remoto a dispositivos, proporcionando una forma de visualizar y controlar la pantalla de un dispositivo desde otro.
    - Team Viewer y Any Desk también permiten el acceso remoto, pero utilizan sus propios protocolos patentados para establecer conexiones, lo que puede ofrecer diferentes características y rendimiento en comparación con VNC y SPICE.
2. Propósito principal:
    
    - VNC y SPICE son comúnmente utilizados en entornos de administración de sistemas y virtualización, donde se requiere acceder y controlar dispositivos de manera remota.
    - Team Viewer y Any Desk se utilizan tanto para fines comerciales como personales, incluyendo soporte técnico remoto, colaboración en proyectos, reuniones virtuales, entre otros.
3. Rendimiento:
    
    - SPICE, especialmente en entornos de virtualización, tiende a ofrecer un mejor rendimiento en términos de velocidad y calidad de visualización en comparación con VNC.
    - Any Desk se destaca por su rapidez y baja latencia en la transmisión de datos, lo que puede proporcionar una experiencia de usuario más fluida en comparación con Team Viewer en algunas situaciones.
4. Características adicionales:
    
    - Team Viewer y Any Desk ofrecen funcionalidades adicionales como transferencia de archivos, chat integrado, colaboración en línea y reuniones virtuales, que pueden no estar presentes o ser limitadas en VNC y SPICE.
5. Enfoque en la seguridad:
    
    - Tanto VNC como SPICE proporcionan funcionalidades de seguridad básicas, pero pueden requerir configuraciones adicionales para garantizar una conexión segura.
    - Team Viewer y Any Desk tienen enfoques más robustos en cuanto a la seguridad, con características como cifrado de extremo a extremo y autenticación multifactor, lo que puede proporcionar un nivel más alto de protección para las conexiones remotas.
# Resumen
Mientras que VNC y SPICE son más comúnmente utilizados en entornos de administración de sistemas y virtualización, Team Viewer y Any Desk son más versátiles y se utilizan tanto en entornos profesionales como personales para una amplia gama de propósitos, con un enfoque adicional en la velocidad, la seguridad y las características adicionales.  

# Referencias
[1]  C. de, “VNC,” _Wikipedia.org_, Apr. 12, 2005. https://es.wikipedia.org/wiki/VNC (accessed Mar. 05, 2024).

‌[2] QNAP Systems, Inc, “How to use the SPICE client (virt-viewer) to connect to a VM console?,” _QNAP Systems, Inc. - Network Attached Storage (NAS)_, 2024. https://www.qnap.com/en/how-to/tutorial/article/how-to-use-the-spice-client-virt-viewer-to-connect-to-a-vm-console#:~:text=It%20allows%20users%20to%20see,VMs%20via%20the%20SPICE%20client. (accessed Mar. 05, 2024).

‌