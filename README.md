# Honeypot-RedLocal | Implementación y Análisis de un Honeypot SSH 

Descripción

Implementé un honeypot(Cowrie) SSH en un entorno Linux para analizar el comportamiento tras comprometer el sistema. Se simularon actividades de post-explotación comunes para observar los comandos utilizados por los atacantes y estudiar patrones de reconocimiento y enumeración del sistema.

Actividades realizadas:

  - Despliegue de un honeypot SSH en entorno Linux.

  - Simulación de actividad atacante para analizar comportamiento post-explotación.

  - Observación de técnicas de enumeración del sistema y reconocimiento de red.

  - Análisis de logs generados por intentos de acceso y comandos ejecutados.

  - Identificación de patrones de actividad maliciosa comunes en accesos SSH comprometidos.

  - Escaneo de puerto (2222) 

Tecnologías utilizadas:

  - Linux

  - SSH

  - Honeypots (Cowrie)

  - Análisis de logs

  - Conceptos de post-exploitation

# Reconocimiento y Movimiento en el Sistema Captados

1. Reconocimiento del sistema

``` whoami
   id
   uname -a
   hostname
   pwd ```

Distribución, Usuarios del Sistemas y Usuarios Conectados
   
 ``` cat /etc/os-release

    cat /etc/passwd

    who
    w ```

2. Enumeración del sistema

 Archivos importantes del sistema

``` ls
    ls -la

    find / -name "*.txt" 2>/dev/null ```

Ver historial de comandos:

``` cat ~/.bash_history ```

