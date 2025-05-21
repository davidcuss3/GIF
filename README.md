Creador de GIF Simple
Este script de Python genera un archivo GIF animado a partir de una secuencia de imágenes PNG.

Requisitos
Para ejecutar este script, necesitas tener instalada la librería imageio en tu entorno Python.

Puedes instalarla usando pip:

Bash

pip install imageio
Uso
Coloca tus imágenes: Asegúrate de que las imágenes que quieres usar (team-pic1.png, team-pic2.png, etc.) estén en el mismo directorio que tu script de Python (.py). Si tus imágenes están en otro lugar, deberás especificar la ruta completa a ellas en el código.

Ajusta filenames (Opcional): Edita la lista filenames en el script para incluir los nombres exactos de todos los archivos PNG que deseas convertir en GIF.

Python

filenames = ['team-pic1.png', 'team-pic2.png', 'otra-imagen.png'] # Agrega o elimina según sea necesario
Ejecuta el script: Abre tu terminal o línea de comandos, navega hasta el directorio donde guardaste el script y ejecútalo:

Bash

python tu_script.py
(Reemplaza tu_script.py con el nombre real de tu archivo Python, por ejemplo, create_gif.py)

¿Qué hace?
El script realizará los siguientes pasos:

Lee cada archivo de imagen PNG especificado en la lista filenames.
Crea un archivo GIF llamado team.gif en el mismo directorio donde se ejecuta el script.
El GIF tendrá una duración de 500 milisegundos (0.5 segundos) por cuadro.
El GIF se reproducirá en un bucle infinito (loop = 0).
