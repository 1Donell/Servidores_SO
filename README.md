![universidad-simon-bolivar-9807a](https://github.com/1Donell/Servidores_SO/assets/88102319/c1a08c6b-0efd-4579-bc04-2a78f52a44a0)

# Proyecto Final del Curso de Sistemas Operativos - Universidad Simón Bolívar, Cúcuta

## Introducción

Bienvenidos al repositorio del proyecto final del curso de Sistemas Operativos de la Universidad Simón Bolívar, sede Cúcuta, correspondiente al semestre 2024-1. Este proyecto tiene como objetivo diseñar y configurar una topología de red específica utilizando herramientas de virtualización.

## Descripción del Proyecto-Laboratorio

La actividad final del curso consiste en:

1. **Diseñar la estructura de red** siguiendo la topología indicada en la imagen adjunta.
2. **Lanzar los servidores** `serverManchester`, `serverMadrid` y `serverOslo` utilizando Debian (última versión o la versión estable anterior), y el `serverParis` utilizando Ubuntu Server (última versión o la versión estable anterior).
3. Cada servidor debe ser una máquina o instancia independiente.
4. La revisión de configuraciones se hará comenzando por el servicio DHCP, seguido por los demás servicios.
5. **Elaborar un informe** detallando todo el proceso de desarrollo y configuración del laboratorio.
6. **Realizar una presentación** para la sustentación del proyecto.

### Topología de Red

![Diagrama del Proyecto](./Diagrama%20proyecto%20S.O.png)

En este proyecto se implementarán los siguientes servicios:
- `serverManchester` (192.168.1.30): SFTP con VSFTPD.
- `serverMadrid` (192.168.1.20): DNS con BIND y servidor web con NGINX.
- `serverOslo` (192.168.1.10): DHCP con ISC DHCP.
- `serverParis` (192.168.1.5): File Server con SMB.

## Enlaces

Para más detalles y documentación, visite la [Wiki del Proyecto](https://github.com/1Donell/Servidores_SO/wiki).

---

**Nota:** Este repositorio contiene la documentación y los archivos necesarios para llevar a cabo la configuración y pruebas del proyecto.

