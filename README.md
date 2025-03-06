# Hackear Wifi con Termux y Routersploit

Este proyecto ilustra cómo instalar y utilizar el framework [Routersploit](https://www.github.com/threat9/routersploit) en Termux para identificar vulnerabilidades en redes WiFi comunes.

**Advertencia:**  
El uso de herramientas de hacking contra redes sin autorización es ilegal. Este código se proporciona exclusivamente con fines educativos y en entornos controlados donde tengas permiso para realizar pruebas de seguridad.

## Contenido del Proyecto

- **hack_wifi.sh:**  
  Un script de Bash que automatiza la instalación de Python, Git, la clonación del repositorio de Routersploit, la instalación de dependencias y el inicio de la herramienta.

- **Este README.md:**  
  Documentación básica sobre el uso correcto y las advertencias pertinentes.

## Requisitos Previos

- Tener Termux o una terminal de Linux/Android.
- Conexión a internet para poder descargar e instalar las dependencias necesarias.

## Instrucciones de Uso

1. Abrir Termux y ejecutar el script:
    ```bash
    chmod +x hack_wifi.sh
    ./hack_wifi.sh
    ```
2. Una vez iniciado Routersploit, puedes usar los siguientes comandos en la línea de comandos de la herramienta:
    - `use scanners/autopwn` para buscar vulnerabilidades.
    - `set target <IP>` para especificar la dirección IP del router objetivo.
    - `set http_port 80` para configurar el puerto HTTP.
    - `run` para ejecutar el exploit y listar las vulnerabilidades encontradas.
    - `use <nombre_de_vulnerabilidad>` para concentrarte en una vulnerabilidad específica.

## Nota Importante

Este script y documentación son únicamente para propósitos educativos. Asegúrate de tener todos los permisos necesarios al ejecutar estas herramientas y adopta siempre conductas éticas en el ámbito de la seguridad informática.
