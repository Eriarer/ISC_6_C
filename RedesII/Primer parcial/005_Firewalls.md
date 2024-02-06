**Firewall de la Red**
Servidores de seguridad, son una determinación de la vieja estrategia. En las redes es posible el  mismo truco, una compañía debe de tener muchas redes LAN conectadas de forma arbitraria, pero todo el tráfico que entra y sale de la compañía debe de pasar por el *firewall*.
- Una entrada, isa salida
El *firewall* actúa como un filtro de paquetes. Inspecciona todos y cada uno de los paquetes entrantes y salientes. Si un paquete no *cumple* cierto criterio son simplemente descartan.

Los **criterios de filtrado** se proporcionan como reglas o tablas que listan *orígenes* y *destinos* aceptables, bloqueados y reglas *predeterminadas* acerca de lo que se debe hacer con los paquetes que entran y salen a otras máquinas.
- El origen o destino podría consistir en una dirección IP y un puerto.
  
Los puertos indican el servicio deseado:
- TCP 25 *correo*
- TPC 80 *HTTP*
Otros pueden estar simplemente bloqueados, algunos no se bloquean tan fácilmente.  El problema  es que los administradores de red desean *seguridad*, pero no se puede cortar la comunicación con el mundo exterior. 
> [!note] DMZ
> Aquí  es donde pueden ser útiles los arreglos coo la DMZ (Zona DesMilitarizada).  La *DMZ* es la parte de la red de la empresa que está *fuera* del *perímetro* de seguridad; todo puede pasar.
> La DMZ permite publicar servicios que no deben estar dentro de la LAN.  

El firewall ahora se puede configurar para bloquear el tráfico TCP entrante al puerto 80, de modo que las computadoras no puedan usar el puerto para atacar las computadoras de la red interna.
Con el tiempo, los firewall se han vuelto mucho más sofisticados en una carrera armamentista contra los atacantes. 
