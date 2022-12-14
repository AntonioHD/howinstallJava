# Tarea 9.- instalación de Netbeans en el SO

* Autor: Antonio Hernández Domínguez
* Curso: 1º DAW 2022/2023
* Asignatura: Entornos de desarrollo
* Tema 3: Instalación y uso de entornos de desarrollo

***

<div align="justify">

# Indice

## [1. Introducción](#id0)
## [2. Prerrequisitos](#id1)
## [3. Instalación de Netbeans](#id2)
## [4. Instalación a través de WGET](#id3)
## [5. Ejecutar Netbeans](#id3)
## [6. Establecer variables de entorno](#id4)
## [7. Verificar la instalación](#id5)

# Introducción<a name="id0"></a>

  NetBeans es un IDE popular para desarrollar aplicaciones Java. Esto permite desarrollar aplicaciones a partir de un conjunto de componentes de software modulares llamados módulos. NetBeans está disponible para ejecutarse en sistemas operativos populares como Windows, macOS, Linux.

<div align="center">
  <img src="https://www.linuxadictos.com/wp-content/uploads/apache-netbeans.jpg" width="250px">
</div>


## Prerrequisitos<a name="id1"></a>

  Recuerda que para la instalación de __Netbeans__ debes de tener instalado __Java__. Los pasos para realizar su instalación y configuración se encuentra en el siguiente [enlace](tarea-jdk.md).

  Para verificarlo recuerda ejecutar el siguiente enlace:

  ```console
  java -version
  ```

<img src=".files/00.png">

## Instalación<a name="id2"></a>

  Los paquetes Snap son paquetes de software universales prediseñados que se envían con las bibliotecas y dependencias requeridas por el paquete de software. Son independientes de la distribución y se pueden instalar en cualquier distribución principal de Linux. Los snaps son populares ya que no requieren ninguna dependencia durante la instalación, lo que hace que el proceso de instalación sea fluido y sin errores.

  Para instalar la edición Netbeans, ejecute el siguiente comando:

```console
sudo snap install netbeans --classic
```

  La instalación finalizará cuando veas el sigueinte mensaje:

  ```console
  netbeans 12.5 from Apache NetBeans✓ installed
  ```

<img src=".files/01.png">

En este caso, el comando "sudo snap" no nos ha permitido realizar la instalación con lo que probaremos a continuación a instalarlo con "wget".

## Instalación a través wget (Cualquier distribución Linux)<a name="id3"></a>

Teniendo en cuenta que has completado la instalación de __java__ en la tarea anterior, puedes realizar la instalación de Netbeans 12.5 a través de __wget__. De esta forma se puede realizar la instalación en ___cualquier distribución de linux___.

Los pasos son los siguientes:

- Abre un navegador, navegue hasta la página de descarga de NetBeans IDE y descargue el último script de instalación de NetBeans IDE ([ Apache-NetBeans-12.5-bin-linux-x64.sh](https://netbeans.apache.org/download/nb125/nb125.html) ) para su distribución de Linux instalada.

  Alternativamente, también puede descargar el script de instalación de NetBeans IDE en su sistema a través de la utilidad wget, con el siguiente código:
  ```console
  wget -c  https://archive.apache.org/dist/netbeans/netbeans/12.5/Apache-NetBeans-12.5-bin-linux-x64.sh
  ```

<img src=".files/02.png">
  
- Una vez completada la descarga, navegue hasta el directorio donde se descargó el instalador de NetBeans IDE y ejecute el siguiente comando para que el script del instalador sea ejecutable y comience a instalarlo.
  Otorgamos permisos de ejecución:

  ```code
  chmod +x Apache-NetBeans-12.5-bin-linux-x64.sh 
  ```

  Ejecutamos el script de instalación

  ```code
  ./Apache-NetBeans-12.5-bin-linux-x64.sh
  ```

<img src=".files/03.png">
<img src=".files/04.png">

- Después de ejecutar el script de instalación anterior, la “ Página de bienvenida ” del instalador se deben de seguir los pasos para personalizar la instalación (lenguajes soportados, etc).

<img src=".files/05.png">
<img src=".files/06.png">

# Ejecutando Netbeans 12

  Ahora que Netbeans está instalado en su sistema Ubuntu, puede iniciarlo escribiendo netbeans en su terminal o haciendo clic en el icono de Netbeans ( Activities -> Netbeans).

  
<img src=".files/05_.png">

<div align="center">
  <img src="https://liukin.es/wp-content/uploads/2021/10/Como-instalar-Netbeans-en-Ubuntu-Linux.png" width="250px">
</div>

  Una vez que se cargue el IDE de Netbeans, se le presentará la página de inicio.

</div>
