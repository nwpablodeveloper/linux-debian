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

<table>
    <tbody>
        <tr>
            <td colspan="2" align="center">COMANDOS IMPORTANES</td>
        </tr>
        <tr>
            <td>Comando</td>
            <td>Función</td>
        </tr>
        <tr>
            <td>Ctrl + c</td>
            <td>Cancela el comando en ejecución</td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                COMANDOS SIN MÉTODOS Y SIN ARGUMENTOS
            </td>
        </tr>
        <tr>
            <td>who</td>
            <td>Muestra el usuario actual, el método de conexión, fech y hora</td>
        </tr>
        <tr>
            <td>clear</td>
            <td>Limpia la terminal</td>
        </tr>
        <tr>
            <td>date</td>
            <td>Muestra la fecha y hora del sistema</td>
        </tr>
        <tr>
            <td>ls</td>
            <td>Muestra el contenido del directorio que estamos</td>
        </tr>
        <tr>
            <td colspan="2" align="center">
                COMANDOS ARGUMENTOS
            </td>
        </tr>
        <tr>
            <td>ping "argumento"</td>
            <td>Envia un ping de conexión a una IP</td>
        </tr>
        <tr>
            <td>df -h</td>
            <td>Muestra la configuración actual de las unidades de almacenamiento</td>
        </tr>
        <tr>
            <td>cd "direcotorio"</td>
            <td>Accedemos al directorio</td>
        </tr>
        <tr>
            <td>cd ..</td>
            <td>Retrocedemos 1 directorio</td>
        </tr>
        <tr>
            <td>cd ../..</td>
            <td>Retrocedemos 2 directorios</td>
        </tr>
        <tr>
            <td></td>
            <td></td>
        </tr>
    </tbody>
</table>


### [Cambiar de usuario]()
el usuario "root" es el usuario administrador del sistema por defecto
```
    su -
    // 1. Nos va a pedir la contraseña con la que instalamos Linux
    // 2. el prompt va a tener root@nombre-compu:~# (~# nos indica que somos administrador)
```

### [Comandos para visualizar Hardware]()

```
    df -h
    // Te muestra la configuración actual de las unidades de almacenamiento del sistema. 
```
```
    free -m
    // Te muestra el estado de la RAM
```

### [Instalar paquetes con APT]()
El comando apt nos sirve para buscar librerias que no temos instaladas en el Sistema
```
    apt search "nombre-paquete"
    // Busca si el paquete esta diponible
```
    > Ej: apt search htop
```
    apt install "nombre-paqute"
    // apt install htop
```

    
### [Comandos para visualizar Sofware]()
```
    top
    // Nos muestra dinamicamente todos los procesos activos
```
```
    htop
    // apt install htop
    // Nos muestra dinamicamente todos los procesos activos de forma mas detallada
```