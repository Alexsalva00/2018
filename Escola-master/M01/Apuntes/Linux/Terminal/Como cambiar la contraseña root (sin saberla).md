# Contraseña Root o Superusuario
* Segun la distro, la forma de hacerlo cambia.
## Fedora
* Para empezar tenemos que interrumpir el inicio del Grup, pulsando la tecla "E" cuando aparezca en la pantalla.
* Vamos a la linea Linux16 y cambiamos "rgbh quiet" por "rd.break enforcing= 0"
* Pulsamos "CTRL+X" para seguir con el proceso de inicio.
* (Si el sistema esta encriptado nos pedira la contraseña LUKS)
* Al hacer esto conseguimos que nuestro fedora inicie en modo de emergencia.
* Montamos el disco duro con el comando "mount -o remount, rw / sysroot"
* Usamos el comando "chroot / sysroot", para acceder al sistema.
* Ejecutamos "passwd" y ponemos la nueva contraseña root 2 veces.
* Escribimos "exit" 2 veces para reiniciar el pc
* Cuando reiniciemos el ordenador, inicamos sesión como usuarios root con nuestra nueva contraseña, y añadimos "restorecon -v /etc/shadow"
para restaurar los cambios del grup.
* Finalmente usamos este comando "setenforce 1" y todo listo.
