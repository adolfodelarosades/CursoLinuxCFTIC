# CursoLinuxCFTIC

Profesor: Jose Luis
Ordenador del Profe: `\\10.2.4.252\linux

## Instalación de Linux

* Tener instalada **Oracle VM Virtual Box Administration**

Abrir el Oracle VM y crear uno nuevo:

* Nuevo
   Nombre: mongo
   Tipo: Linux
   Version Oracle 64 bit
   4 Gigas Ram
   Discu Duro Crear
   VDI
   Reservado Dinámico
   60 GB
   
* Se creo Mongo
   Botón Derecho Configurar
   * Sistema
      Placa Base
      Procesador 4
      Limite de Ejecución 80%
   * Pantalla 
      Mem. Video 64
   * Audio (Deshabilitar)
   * USB (Deshabilitar)
   * Almacenamiento
      En el CD(Vacio)
        Seleccionar el ISO Descargado
        
**YA QUEDO MONTADO**

## ARQUITECTURAS

x86   32 bits     Intel
x64   64 bits     Intel
RIST
PARK

## INICIAR MAQUINA VIRTUAL

* Seleccionar mongo
* Presionar el botón Iniciar
  Debe decir:
  **Welcome to Oracle Linux Server 6.7**
* Seleccionar el primer `Ìnstall`
* Disc Found
  skip
  Idioma: English
  Teclado: Spanish
  Type of devices: Basic
     Yes, discard
     
  Hostname: profe.aula24.pum
  Configure Network
  Sitio: Madrid
  Root Password: cangetin
  Confirm: cangetin
  Tipo Instalacion: Next
  Write Changes dise
  Opciones en la Instalación: (Va por paquetes tiene repositorios)
  Basic Servet: Next
     Instala Packages (rpm) 657
     Google Oracle linux packages
     
     
 Una vez finalizado todo pulsar el comando:
 
 `> reboot`
 
 Puede que cuando se reiniciara instalara de nuevo pero no fue el caso.
 
 Pide datos:
 
 ```
 user: root
 password: *******
 ```
 
 ## COMANDOS
 
 En Linux todos los comandos son ficheros.
 
 `who -m`   En que terminal estoy `tty1`
 
 `who am i` Quien soy `/dev/tty1`
 
 `who`      Cuantos usuarios hay en la maquina
 
 `man`      Ayuda
 
 `man who`  Ayuda de `who` Salir con `q`
 
 `man man`  Ayuda de la ayuda
 
 `clear`    Limpiar ventana
 
 `pwd`      Donde estoy
 
 `ls`       Lista contenido
 
 `cd`       Cambia de carpeta
 
 `cd /root` Cambia a la carpeta `root`
 
 #### Existen varias carpetas importantes:
 
 nombre | Descripción
 -------|------------
 `/dev` | Dispositivos
 `/home`| Home de los usuarios
 `/bin` | Binarios
 `/sbin`| Binarios
 `/opt` | Software de terceros
 `/usr` | Librerias y links Modulos
 `/etc` | Configuraciones
 `/etc/init.d` | Scripts de arranque
 `/etc/profile` | P
 `/etc/yum.d` | Repositorios de Software
 
 ### RUTAS
 
 Existen dos tipos de rutas:
 
 * Relativas
 * Absolutas
 
 Ejemplo de rutas Relativas:
 ```sh
 cd /etc
 cd init.d
  ```
 
 Ejemplo de ruta Absoluta:
 ```sh
 cd /etc/init.d
  ```
 
 ## Más Comandos
 
 `ls -l atd`
 
 `file atd`     Que tipo de fichero es: `POSIX shell script`
 
 `./atd`        Ejecución de un programa relativo
 
 `/etc/init.d/atd`  Ejecuciíon con ruta absoluta
 
 `cd /root`     Cambiar a `root`
 
 `ls -l`        Listar en horizontal
 
 `ls -a`        Muestra archivos ocultos
 
 `ls -l | wc -l`  Cuantas líneas existen (Pone una más que archivos)
 
 `ls -a | wc -l`  Cuantas líneas existen (Pone una más)
 
 `ls -la`       Lista en horizontal y archivos ocultos.
                Se muestran dos directorios
                .       Carpeta Actual
                ..      Carpeta Padre
                
`ls -lrta`      Ordena por fecha ascendente

`cd /tmp`       Cambia a `tmp`  **SI SE LLENA `tmp` SE PUEDE LIAR**

`mkdir carpeta1`  Crea `carpeta1`

`mkdir /tmp/carpeta2` Crea `carpeta2` dentro de `tmp`

`mkdir /tmp/carpeton/lunes`   Intenta crear la carpeta `lunes` pero hay **ERROR** por que no existe la carpeta `carpeton`

`mkdir -p /tmp/carpeton/lunes`   `-p` crea la carpeta `lunes` aun que no exista la carpeta `carpeton` la cual también crea






                
                
 
 
 
 
 `cd`       Cambia de carpeta
 
 
  
`CTRL DE LA DERECHA`  Sale de la ventana y dandole click a la ventana entramos de nuevo.

  
  


