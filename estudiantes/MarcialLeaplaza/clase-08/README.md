# clase-08
## 04/25/2024

## To do list + Descripcion de proyecto:

Materiales que ya tengo:

``
Controlador MIDI
``

``
Computador
``

``
Grasshopper para controlar
``

Materiales que tengo que conseguir:

``
Cable para conectar mi controlador al computador.
``

``
Plug-ins que me permitan usar grasshopper como MIDI output.
``
## Proyecto explicado en una frase:

Panel de control MIDI para crear sables de luz.

## Proyecto explicado en un parrafo:

Conectar un controlador MIDI real a un codigo de grasshopper que sirve para crear y customizar modelos 3D de sables de luz de Star Wars, de modo que con este se puedan controlar todos los parametros del diseño, de tal manera que se pueda jugar con el codigo sin la necesidad de usar un mouse, y que sea mas comodo interactuar con los distintos parametros en forma de sliders, toogles y selectores.

## Proyecto explicado con 5 hashtags:

#MIDI #StarWars #Grasshopper #3DModel #Interface

## Empieza el desarrollo del proyecto final.

Mi primer objetvo será controlar al menos una cosa con el controlador OP-1 del profesor.

Para ello necesito usar MIDI en grasshopper y ver como usar el controlador como input.

Encontre un foro en grasshopper3d [aquí](<https://www.grasshopper3d.com/group/ghowl/forum/topics/physical-sliders?page=4>).

En el foro encontre un primer plugin. No resulto tan util ya que en este caso lo que se quiere lograr es generar inputs desde rhino, traducirlo a MIDI y con eso hacer musica. En mi caso es al revez, ya que yo deseo que rhino sea el output, no el input.

El segundo plugin que encontre es mas util, ya que este si permite que grasshopper sea el output. El plugin lo puedes encontrar [aqui](<https://www.grasshopper3d.com/forum/topics/mandrill-midi-realtime-bridge-for-grasshopper>)

en este [video](<https://www.youtube.com/watch?v=WYcriR227Dg>) se ve bien lo que quiero lograr.

Lamentablemente el video es de hace 14 años y no hay info adicional sobre el plug-in o la forma en la que logro conectar todo.

Por hoy e cncentrare en tratar de hacer funcionar un programa llamado "mandrill" que encontre en el primer foro.

Para ello primero debo crear un environment variable, para lo cual debo ir a settings >> about >> advanced system settings >> evironment variables

Cuando copié el path que le da valor al environment, lo copia automaticamente con comillas ("), por lo que tuve que borrarlas manualmente.

Mandrill viene con un codigo de previews que no parece funcionar siguiendo los pasos del README, la verdad es que el readme deja bastante que desear. Los readme son muy imprtantes!!!

Mi problema actualmente es que Mandrill parece no funcionar aun despues de haber seguido los pasos del README.
