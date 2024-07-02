## COMANDOS I

![](comandos.jpg)

### [Linux Documentation Commands](https://linux.die.net/)

- Interprete de Comandos ( Shell de Linux)
Es un programa que se ejecuta siempre que un usuario se conecta al sistema.
Su función principal es interactuar en entre el usuario.

![](interprete-de-comandos.jpg)

### [Comandos:]()
Linux es Key sensitive, vamos a poder esciribir un comando siempre que este el signo
(Dolar) en la terminal Shell.
> Ejemplo del prompt
> nombre-usuario@nombre-compu:/$

```linux
    Ctrl + C
```
    * Cancela el comando en ejecución. 

### [Comandos sin métodos y sin argumentos:]()
```who```
    * Nos trae el usuario actual del sistema, el método de conexión que se esta usando
     y la fecha y hora
```clear```
    * Limpia la termainal.
```date```
    * Muestra la fecha y hora actual
```ls```
    * Nos muestra el directorio actual

### [Comandos con argumentos]()
```ping "argumento"```
    > Ej.
    > 
    > ping www.google.com
    >
    > ping 192.168.1.1
```df -h```
    * Te muestra la configuración actual de las unidades de almacenamiento del sistema. 
```cd "directorio"```
    * Accedemos al directorio
```cd ..```
    * Regresamos 1 directorio

### [Cambiar de usuario]()
el usuario "root" es el usuario administrador del sistema por defecto
```su -```
    1. Nos va a pedir la contraseña con la que instalamos Linux
    2. el prompt va a tener root@nombre-compu:~# (~# nos indica que somos administrador)

### [Comandos para visualizar Hardware]()

```df -h```
    * Te muestra la configuración actual de las unidades de almacenamiento del sistema. 
```free -m```
    * Te muestra el estado de la RAM

### [Instalar paquetes con APT]()
El comando apt nos sirve para buscar librerias que no temos instaladas en el Sistema
```apt search "nombre-paquete"```
    * Busca si el paquete esta diponible
    > Ej: apt search htop
```apt install "nombre-paqute"```
    > apt install htop

    
### [Comandos para visualizar Sofware]()
```top```
    * Nos muestra dinamicamente todos los procesos activos
```htop```
    * apt install htop
    * Nos muestra dinamicamente todos los procesos activos de forma mas detallada