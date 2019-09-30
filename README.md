# divicion logica de un disco duro
ESTRUCTURA LÓGICA DE UN DISCO DURO:

La estructura lógica de un disco duro esta formado por:

    Sector de arranque.
    Espacio particionado.
    Espacio sin particionar.

Sector de arranque: Es el primer sector de un disco duro en él se almacena la tabla de particiones y un programa pequeño llamado Master Boot. Este programa se encarga de leer la tabla de particiones y ceder el control al sector de arranque de la partición activa, en caso de que no existiese partición activa mostraría un mensaje de error.

Espacio particionado: Es el espacio del disco que ha sido asignado a alguna partición.

Espacio sin particionar: Es el espacio del disco que no ha sido asignado a ninguna partición por lo tanto no es accesible.

