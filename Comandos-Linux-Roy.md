## ***Comandos en general para Linux***

 - `pwd` ------------------------------------> saber en que directorio me 
   encuentro 
 - `sudo apt update` ------------------------> tener acceso a un comando y poder actualizar 
 - `sudo apt install` -----------------------> tener acceso y poder instalar un paquete 
 - `clear`   ----------------------------------> limpiar la terminar 
 - `sudo apt search` ------------------------> buscar el paquete que se quiere instalar 
 - `lsb_release -a` -------------------------> cual es la version del SO 
 - `uname -a` -------------------------> version del kernel 
 - `mkdir` ----------------------------------> crear un directorio 
 - `mkdir  "Nueva Carpeta"` ------------------> crear una nueva carpeta 
 - `ls`  -------------------------------------> lista de directorios  
 - `ls -l` ----------------------------------> lista de archivos 
 - `man ls` ---------------------------------> se usa para saber el significado de un comando
 - `ip addr` --------------------------------> se usa para saber la direccion ip 
 - `sudo apt install`   
 - `openssh-server`---------> instalar el paquete de transferencia de archivos
 - `touch "archivo.txt"` --------------------> crear un archivo  
 - `nano "archivo.txt"` ---------------------> permite editar el contenido de un archivo 
 - `cat "archivo.txt"` ----------------------> permite ver el contenido de un archivo 
 - `more "archivo.txt"` ---------------------> permite ver el contenido de un archivo 
 - `ps -aux`  --------------------------------> ver lista de procesos que están corriendo 
 - `pstree` ---------------------------------> ver procesos 
 - `htop` -----------------------------------> ver procesos 
 - `grep` -----------------------------------> buscar texto en cualquier lugar 
 - `ps -aux | grep "firefox"` ---------------> se concatenan comandos con 
   | y permite encontrar el proceso de firefox 
  - `kill -9 "numero de proceso"` ------------> se elimina el proceso, se cierra 
  - `root`  -----------------------------------> usuario administrador 
  - `su root` --------------------------------> permitir el acceso al usuario admin

***

## Algunos comandos utilizados en Manjaro Actividad 4 de Manjaro

***

 1. `sudo pacman -Syuu`
 2. `sudo pacman -S unrar zip unzip p7zip gzip bzip2`
 3. `sudo pacman -S yay`
 4. `sudo yay -S --needed base-devel`
 5. `yay -S google-chrome`
 6. `sudo pacman -S neofetch`
 7. `uname -a`
 8. `sudo useradd -m nombredeusuario -G wheel -p passworddelusuario`
 9. `cd,  mkdir, chmod, chown, rmdir, rm`
 10. `ls /bin`
 11. `cp -rv /etc/a* $HOME/dir004 1> $HOME/dir003/dircuatro/archivo2`
 12. `ls -l $HOME 1> $HOME/dir003/dircuatro/archivo3`
 13. `cp /etc/profile $HOME/dir003/dircuatro/`
 14. `mv`
 15. `cp`
 16. `kill`
 17. `chown`
 18. `chmod`
 19. `nano`
 20. `touch`

## ***Comandos Docker***


- `docker images` 
-  `dockker pull [imagen o contenedor]`|
 - `docker ps -a`
 - `docker info`
 - `docker network ls`
 - `docker network create --dirver bridge`
 - `docker run [imagen]`
 - `docker run -ti`
 - `docker rm`
 - `docker stop`
 - `docker rmi`
 - `vim Dockerfiledocker build -t [contenedor]`
 - `vim Dockerignoredocker service create --name web`

Link del repositorio en GitHub

    [https://github.com/royjavier12/Comandos-Linux-Roy/blob/08683b7a764aac91051b251721507d76f2b799d3/Comandos-Linux-Roy.md](https://github.com/royjavier12/Comandos-Linux-Roy/blob/08683b7a764aac91051b251721507d76f2b799d3/Comandos-Linux-Roy.md)

