## Hipervisor
Un *hypervisor* conocido como supervisor de máquina virtual, es un software que crea y ejecuta *VM* y además, aísla el sistema  OS y recursos de las VM. Permite crearlas y gestionarlas [1]

### Tipos de hipervisores
Existen 2 tipos de hipervisores.
#### Tipo 1: Bare metal
También conocido como hipervisor nativo o de servicio dedicado, se ejecuta directamente en el HW del host y gestiona los OS del invitado.   
Este tipo se suele encontrar dentro de centros de datos. [1]
#### Tipo 2: Alojado
El hipervisor alojado, se ejecuta en un OS convencional como una paca de SW o APP. Extrae los OS de los invitados del OS del host.  Los recursos de la VM se programan en el OS, después se ejecuta en el HW. [1]
## Hiper-V
Hiper-V es una tecnología de virtualización para windows; permite ejecutar varios OS como VM en windows.  
Específicamente proporciona virtualización en HW, lo que es que cada VM se ejecuta en HW *virtual*. [2]
## VMware vSphere
Es una plataforma de virtualización de VMware, la cual transforma los centros de datos en infraestructuras de computación agregadas que incluye los recursos coo: redes, CPU y almacenamiento.
### vSphere
La vSphere administra infraestructuras como un entorno unificado y le proporciona las herramientas para administrar los data centers de dicho entorno. [3]
## ProxMox
Es un servicio empresarial que ofrece soluciones con funcionalidad y acceso completo para todos.  [4]  
Es una plataforma open-source para manejar servidores mediante virtualización. Integra KVM hypervisores, contenedores de Linux, almacenamiento definido por SW. [5]  
# Referencias
[1]  
“¿Qué es un hipervisor? Hypervisor,” _Redhat.com_, 2024. https://www.redhat.com/es/topics/virtualization/what-is-a-hypervisor (accessed Feb. 22, 2024).

‌[2]  
scooley, “Introducción a Hyper-V en Windows 10,” _Microsoft.com_, Jul. 13, 2023. https://learn.microsoft.com/es-es/virtualization/hyper-v-on-windows/about/ (accessed Feb. 22, 2024).

‌[3]  
“Documentación de VMware vSphere,” _Vmware.com_, 2024. https://docs.vmware.com/es/VMware-vSphere/index.html (accessed Feb. 22, 2024).

‌[4]  
“Proxmox Server Solutions,” _Proxmox_, 2019. https://www.proxmox.com/en/ (accessed Feb. 22, 2024).

[5]  
“Proxmox Virtual Environment,” _Proxmox_, 2019. https://www.proxmox.com/en/proxmox-virtual-environment/overview#:~:text=Proxmox%20Virtual%20Environment%20is%20a,functionality%2C%20on%20a%20single%20platform. (accessed Feb. 22, 2024).

‌
‌