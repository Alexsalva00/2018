# Tipos de Particiones
---
Hay que diferenciar entre el formato o **sistema de archivos** de las particiones (NTFS,Fat32...) 
y el **tipo de partición** (Primaria,Extended...).

Existen 3 tipos de particiones:

## Partición Primaria
---
Solo puede haber **4 particiones primarias, o 3 primarias y una extended**.

Un Disco Duro que esta completamente formateado, 
consiste basicamente en una sola partición primaria que ocupa todo el disco 
y posee un unico sistema de archivos que normalmente la mayoria de los S.O. pueden entenderlo.

## Partición Extendida.
---
Se conoce tambien como una **partición secundaria**.

Dentro de esta partición, puede haber **infinitas lógicas**.

Se creo con la idea de acabar con el limite de 4 particiones en un solo Disco Duro.

Solo puede haber **una Extended en cada Disco Duro**.

**No soporta un sistema de archivos directamente**.

## Partición Lógica
---
Ocupa una porción de la particion **Extended** o tambien puede ocuparla toda.

Se formatea con un tipo especifico de **Sistema de Archivos**.

Puede haber un total de **23 particiones lógicas** en una Extended.
