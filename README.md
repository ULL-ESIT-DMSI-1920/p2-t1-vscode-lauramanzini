# Práctica 3 - VSCode

**Laura Manzini**

alu0101531700@ull.edu.es 

1. [Introducción](#intro)
2. [VSCode y GitPod](#vscgitpod)
3. [Tutorial](#tutorial)
4. [PlugIn SSH FS](#plugin)
5. [Instalación de LiveShare](#liveshare)

<a name = "intro"><a> 
## 1. Introducción

**Visual Studio Code** (VSCode) es un IDE (Integrated Development Environment) que permite de desarrollar código y adémas incluye soporte para la depuración, control integrado de Git, resaltado de sintaxis, finalización inteligente de código, fragmentos y refactorización de código. En inglés esta herramienta es llamada un *code editor*.

Este editor está escrito totalmente en Electron, un framework utilizado para unir Chromium y Node.js en forma de aplicación de escritorio.

Una de las mejores características de este editor es *IntelliSense*. Esta función permite resaltar la sintaxis de todo el código fuente.

VSCode es disponibles sobre los sistemas operativos Windows, macOS y Linux y se puede instalar desde la [pagína principal](https://code.visualstudio.com/download) de la plataforma de forma gratuita.

<a name = "vscgitpod"><a> 
## 2. VSCode y GitPod

La diferencía entre VSCode y Gitpod es bien explicada sobre la [documentación de GitPod](https://www.gitpod.io/blog/visual-studio-online-vs-gitpod).

Como hemos dicho VSCode es un *IDE*, una herramienta que se instala de manera local sobre una máquina y nos permite de hacer cambios al código que luego será sincronizado con el proyecto en desarollo.

El GitPod en cambio es un *Cloud IDE* es decir una herramienta que permite de desarrolar código, hacer cambios a un proyecto sobre la nube así que se sincronizará de manera continua. Adémas GitPod nos permite de acceder a un cualquiera repositorio que tenemos en Git y hacer cambios. 

<a name = "tutorial"><a> 
## 3. Tutorial

Para aprender de manera mejor como utilizar VSCode hay algunos tutorials como el siguiente [tutorial](https://code.visualstudio.com/docs/introvideos/basics).

Abriendo VSCode se pueden ver algunos de los *shortcuts* más util que nos pueden ayudar a utilizar la plataforma.

![vscode start](/Img1_vsc_start.jpg)

Pulsando uno de los comandos podemos:

* Ver todos los comandos
* Abrir un fichero
* Abrir una carpete
* Abrir un fichero recente

En la barra lateral encontramos las funcionalidades principales de VSCode que utilizamos. Si instalamos un plugin sobre VSCode la barra lateral añadirá elementos que nos serían util para el desarollo de un proyecto.

Las funcionalidades princípal van a ser:

* Explorador: nos permite de explorar ficheros y carpetas que hemos abierto sobre la plataforma 
* Buscar: buscamos las coincidencias de una palabra y hacemos modificaciones
* Control de código fuente: permite la integración con git haciendo commits y guardando código  
* Depurar: funcionalidad que permite de depurar los archivos JavaScript. Sierve a ir de linea a linea para depurar cada linea
* Extensiones: instalación y busqueda de extensiones para VSCode

Algunas funcionalidades que van a ser muy util son las siguientes:

* Duplicar la pantalla en la que se está desarollando el código para ver todos los cambios que se han hecho
* Barra de busqueda arriba para encontrar acciones o archivos. Es necesario utilizar el simbolo `>` 
* Trabajar con más documientos abiertos elijiendo la configuración que nos más gusta
* Ver la ruta de navigación del fichero que está abierto

En la *welcolme page* de VSCode es posible encontrar ayuda en el utilizo de la plataforma y también las configuraciónes más util.

Algunos comandos util pueden ser:
* Ctrl + º : división de pantalla



https://www.youtube.com/watch?v=Ijz1mXQm7KU&ab_channel=FalconMasters


<a name = "plugin"><a> 
## 4. PlugIn SSH FS

Una de las ventajas que se obtienen utilizando VSCode es la posibilidad de instalar extensiones que permiten de personalizar la plataforma para su proprio utilizo. 

La extensión SSH FS permite de montar carpetas remotas como carpetas de espacio de trabajo local, iniciar terminales remotos integrados y ejecutar tareas ssh-shell.

![Install plugin](/Img1_sshfs.jpg)

Una *secure shell* (ssh) es un protocolo de red que nos permite de acceder a una shell en remoto a través de una conneción segura.

<a name = "liveshare"><a> 
## 5. Instalación de LiveShare

Para aprender como se utiliza la funcíon de LiveShare de VSCode se puede vistitar la [página oficial](https://code.visualstudio.com/learn/collaboration/live-share) de LiveShare.

![live share install](/Img2_liveshare.jpg)

Esta extención nos permite de colaborar con otras personas en tiempo real para el desarollo de un proyecto. LiveShare permite de hacer llamadas y también inviar mensajes.

Seleccionando la opccíon *Start Collaboration session* se genera de manera automatica un enlace que se puede compartir con 

El unico requisto es que las personas con las que colaboras tengan también instalado en sus maquinas VS Code y la extensión de Live Share.
