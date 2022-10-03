# Erick Josué Gamboa Rodríguez
# Ingresando a la máquina virtual
- Ejecutar `vagrant up` para levantar la maquina o la provisiona si no existe 
- Si desea apagar la maquina ejecute `vagrant halt`
- Si deseas ver árbol de directorio oculto puedes ejecutar `tree . -a`
- Ejecutar `eval "$(ssh-agent -s)"` para inicializar un agente de ssh que nos permita hacer autenticación con otros servidores *solo sirve en el bash de git*
Ejecutar `ssh -add` y la *ruta relativa* para cargar la llave 
Ejecutar `ssh *usuario* y *host*` para conectarnos a la maquina por ssh 
Ejecutar `ssh-keygen -f *ruta*` para limpiar la huella de la maquina, *solamente si se verifica que no se trata de un hackeo*
Ejecutar `cd.ssh / cat llaves autorizadas` para ver la llave privada 
Estando en .ssh se ejecuta `ssh-keygen -t rsa` para generar key ssh
Se le debe setear una contraseña a la llave privada, segundo factor de autenticación 
*se generan las llaves* dos archivos .pub es la llave publica la privada es la que no tiene formato
se copia la llave publica 
se van a la carpeta que los deje conectarse a la maquina y se conectan 
sudo apt-get update
sudo apt-get install vim vim-nox
vim ~/ archivo de llaves autorizadas para editar 
*en vim editando* presiona tecla o y la lleva al final del archivo y le permite insert 
escape sale del insert
:qw guarda y sale
pega la llave 
otra forma de hacerlo es viendo telegram  xD
comprobar que funciona la autenticación: ssh-dd ~/.shh/nombre del archivo de la llave privada y meter contra de la clave y ver que cambia el home de la maquina
ya estando en la maquia vagrant 
vamos a instalar unas varas en la maquina
sudo apt-get update 
comando de telegram para instalar unos paquetes 8:58pm
crear un archivo vhost con la plantilla que va a pasar el profe 21:09
se pega en el web server el archivo 
Desde la maquina virtual lo copio y lo pego en etc/apache2/sites-availible
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


