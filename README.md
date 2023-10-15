# Ponzela Design website


## Desplegar sitio web

1. Abrir una nueva terminal en Visual Studio Code. Para ello, hacer click en el botón ``Terminal -> Nueva Terminal`` de la barra superior. E posible usar el atajo de teclado ``Ctrl+Shift+ñ``.

2. Servir el sitio web usando el commando ``hugo serve --buildDrafts --buildFuture -p 8000``.

3. Abrir con cualquier navegador web la siguiente dirección: http://localhost:8000/

4. Cualquier modificación del sitio web será actualizada en tiempo real. Asegurarse de que los nuevos cambios se han guardado para que se apliquen. Puedes utilizar ``Ctrl+s``. En el panel de pestañas de archivos, si aparece una bolita al lado del nombre del archivo, es que los cambios no se han guardado.

5. Para dejar de servir el sitio web, volver a la terminal y presionar ``Ctrl+c`` para terminar el proceso.


## Registrar cambios con Git

1. Una vez tengamos los cambios deseados y guardados hay que registrarlos usando Git.

2. Visual Studio se integra muy bien con Git. En la parte izquierda del editor se puede encontrar el símbolo de ``Source Control``, para usar Git. Se puede acceder también usando el atajo ``Ctrl+Shift+g``.

3. El panel muestra que archivos han sido creados, modificados o eliminados.

4. Seleccionar los archivos deseados (icono +), nombrar el cambio y registrarlo.


## Subir cambios a GitHub y abrir pull request

1. Escribir en la terminal ``git push``

2. Ir a la pestaña ``pull request`` en GitHub: https://github.com/ponzeladesign/website/pulls

3. Abrir pull request, poner título, descripción y dar a ``create pull request``

4. Una vez creado dar al boton verde ``merge pull request`` y verás un botón de ``confirm merge``

5. Ir a la pestaña ``actions`` y comprobar que se ha cargado todo.

6. Refrescar la rama ``post/generic`` y moverte a ``main`` para comprobar que se han añadido los cambios a la rama en el ``Git Graph``. Refrescar la rama ``main``.

## Abrir web en incognito








