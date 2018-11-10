# MBR 
## Que es?
El registro principal de arranque o registro de arranque maestro como también se conoce (del inglés Master boot record cuyo acrónimo es MBR), 
es un sector de 512 bytes al principio del disco duro que contine una secuencia de comandos necesarios para cargar un sistema operativo
## Que contiene?
### Tabla de particiones
Pesa 64 bytes y contiene 4 registros que definen cada una de las particiones primarias.
### Gestor de arranque
Contien el codigo de arranque y pesa 446 bytes
### Signature
Es la firma de unidad de arranque y pesa 2 bytes

La suma del total da 512, y esto es el MBR
