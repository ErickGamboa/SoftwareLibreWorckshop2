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

habilitar modulos de apache ver en telegran 9:14pm
crear estructura de telegram 9:16
con el comando telegram 9:16
agregar servername telegram 9:21
ver que no haya error de sintaxys telegram 9:24
habilitar el sitio telegram 9:24
reload a apache 
etc/host 



# Comandos importantes para crecimiento personal

pwd donde estoy 
ls que hay donde estoy
cat 


