# MBR DOS
---
## Que es?

* El registro principal de arranque o registro de arranque maestro como también se conoce 
  (del inglés Master boot record cuyo acrónimo es MBR), 
  es un sector de 512 bytes al principio del disco duro 
  que contiene una secuencia de comandos necesarios para cargar un sistema operativo
  
## Que contiene?

### Tabla de particiones

  * Pesa 64 bytes y contiene 4 registros que definen cada una de las particiones primarias.
  
  #### -Reglas 

  * Máximo 4 primarias
  
  * Ha de haber una activa

  * Esta permitido una extended, no activa

  * Dentro de la extended puede haber "n" lógicas

  * Una extended no puede ser activa


### Gestor de arranque

* Contienen el código de arranque y pesa 446 bytes

### Signature

* Es la firma de unidad de arranque y pesa 2 bytes

* La suma del total da 512, y esto es el MBR


# GPT
---
## Que es?
* Es un estándar para la colocación de la tabla de particiones en un disco duro físico. 

* Es parte del estándar Extensible Firmware Interface propuesto por Intel para reemplazar el viejo BIOS del PC, 
  heredada del IBM PC original.

* La GPT sustituye al Master Boot Record usado con el BIOS
