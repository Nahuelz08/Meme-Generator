# Generador de Memes
## Tareas realizadas:
* El color del fondo del contenedor del meme puede ser cambiado.
* Los modos en los que se mezcla el color con la imagen también funcionan.
* El botón restablecer filtros también funcional.
* Utilicé [dom-to-image](https://github.com/tsayen/dom-to-image) y [FileSaver](https://github.com/eligrey/FileSaver.js/) para convertir el DOM en imagen y descargarla.

# Cosas extras que añadí:
* Un input para poder añadir imágenes de forma local.
* Ajusté algunos tamaños de varias cosas que a mi parecer hacían falta.
* Añadí de forma responsive todo lo necesario, adaptando el contenido para todas las vistas y creando la funcionalidad del aside para abrir o cerrarse dependiendo si es Mobile o Tablet al igual que estar fijo en modo Desktop.
* Añadí hovers para ser más amigable a la vista las cosas seleccionables.
* Corregí una función de un candidato anterior, la cual era de los filtros. Dicha función sí aplicaba filtros, pero solo un filtro a la vez, si querías incluir otro filtro sobrescribía el anterior, por lo tanto, solo se podía tener uno. Tuve que recrearla de cero para que funcione como debe.
