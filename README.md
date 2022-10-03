# Erick Josué Gamboa Rodríguez
# Ingresando a la máquina virtual
- Ejecutar `vagrant up` para levantar la maquina o la provisiona si no existe 
- Si desea apagar la maquina ejecute `vagrant halt`
- Si deseas ver árbol de directorio oculto puedes ejecutar `tree . -a`
- Ejecutar `eval "$(ssh-agent -s)"` para inicializar un agente de ssh que nos permita hacer autenticación con otros servidores *solo sirve en el bash de git*
- Ejecutar `ssh -add` y la *ruta relativa* para cargar la llave 
- Ejecutar `ssh *usuario* y *host*` para conectarnos a la maquina por ssh 
- Ejecutar `ssh-keygen -f *ruta*` para limpiar la huella de la maquina, *solamente si se verifica que no se trata de un hackeo*
- Ejecutar `cd.ssh / cat llaves autorizadas` para ver la llave privada 
- Estando en .ssh se ejecuta `ssh-keygen -t rsa` para generar key ssh
- Se le debe setear una contraseña a la llave privada, segundo factor de autenticación 
- *se generan las llaves* dos archivos `.pub` es la llave publica y la privada es la que no tiene el .`pub`
- Se debe copiar la llave publica 
- Se realiza una conexión a la máquina
- Se debe instalar vim y vim - nox con los siguientes comandos `sudo apt-get update` `sudo apt-get install vim vim-nox`
- `vim ~/` archivo de llaves autorizadas para editar 
- *en vim editando* presiona la tecla "o" y lo lleva al final del archivo y donde debes de hacer el insert de la llave copiada
- `:qw` para guardar y salir
- Estando ya conectados a la maquina de vagrant vamos a ejecutar los siguientes comandos para instalar paquetes necesarios `sudo apt-get update` `sudo apt-get install vim vim-nox curl git apache2 mariadb-server mariadb-client php7.4 php7.4-bcmath php7.4-curl php7.4-json php7.4-mbstring php7.4-mysql php7.4-xml`
- Habilitar modulos de apache con el siguiente comando `sudo a2enmod vhost_alias rewrite ssl`
- Ejecutar el siguiente comando para crear una estructura de carpetas necesaria `mkdir -p ~/sites/lfts.isw811.xyz/public`
Agregar servername en el host local 
- Comprobar que no hayan errores de sintaxis `sudo apache2ctl -t`
- Habilitar el sitio `sudo a2ensite lfts.isw811.xyz.conf`
- Reiniciamos apache2 `sudo systemctl reload apache2`
# Comandos importantes para crecimiento personal

`pwd` directorio en el que estoy
`ls` lista de elementos que hay donde estoy
`cat` comando de solo lectura


