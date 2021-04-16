
# ves

VEs ver / vES escuchar

VES comando cuya finalidad es ahorrar la necesidad de recordar los distintos comando para abrir archivos de diferentes formatos, por ejemplo PDF, mp3, mp4, jpg, por mencionar algunos.

Cuando se trabaja desde terminal es realmente molesto tener que abrir un gestor de ficheros para poder visualizar alguna imagen o tener que reproducir algún audio o vídeo, dado que el comando para ejecutar la aplicación encargada de visualizar el elemento tiene un nombre diferente al del programa o  simplemente no recordamos el paquete que usamos para dicha tarea como  tal.

El comando ves nos permitirá ejecutar un solo comando con diferentes formatos de fichero y así agilizando así nuestra experiencia en terminal.

Archivos configurados en "ves" y paquetes utilizados para su funcionamiento:

    Entre paréntesis esta el nombre del paquete o programa utilizado para visualizar dicho fichero

- PDF (evince)
- jpg (ristretto)
- Texto/plano (typora) este paquete fue elegido por ser un excelente editor de Markdown
- svg (inkscape)
- xcf (gim)

Si usted usa algún paquete diferente para visualizar sus ficheros  sustituya el nombre mencionado en la lista anterior por el nombre de su  paquete.



### Instalar

`git clone https://github.com/SolimanHub/comando_ves.git`

`cd comando_ves`

`sudo ln -s /direcion_completa/comando_ves/ves /usr/bin/ves`

### Forma de uso:

`ves archivo.xyz`
