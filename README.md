# Instalación Automatizada Debian 13 Trixie

Sistema automatizado de instalación para Debian 13 Trixie con preseed.  
Soporta BIOS/UEFI y medio de instalación local.  

- Particiones: EFI (FAT32), /boot (ext4) fuera de LVM; LVM para /, /home y /var.  
- Contraseñas codificadas, sin texto plano.  
- Entorno gráfico GNOME.  
- Paquetes adicionales: `firewalld`, `openssh-server`.  
- Configuración automática para todos los ítems de instalación.  
- Tamaños de particiones adaptados al disco disponible.  

Despliegue: La instalación se iniciará en modo desatendido y finalizará automáticamente con un reinicio, dejando el sistema listo para su uso.
