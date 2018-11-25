# Partprobe
El comando **partprobe** se utiliza para informar al **sistema operativo** de los cambios de la **tabla de particiones**.

Partprobe es un programa que **informa al kernel** del sistema operativo de los cambios de la tabla de particiones, 
solicitando que el sistema operativo **vuelva a leer la tabla de particiones**. 

Por ejemplo, si creas una partición nueva en uno de los discos mediante **GParted**, 
hay que ejecutar **partprobe** después para que el núcleo tenga conocimiento de la nueva configuración de partición.
