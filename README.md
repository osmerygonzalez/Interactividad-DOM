# Interactividad-DOM
Proyecto de Interactividad en el DOM implementando un Menú Hamburguesa, boton Modo Oscuro que alterna modo claro/oscuro y un boton leer mas.
Menú Hamburguesa: Funciona para pantallas medianas y pequeñas (por debajo de 768px).
Documento HTML se agregó un Button de menú hamburguesa está contenido dentro de la barra de navegación, representado por un ícono de barras, denominamos la clase como “menu-hamburguesa” y para el i class="fa-solid fa-moon".
El código JavaScript hace que, al hacer clic en el menú hamburguesa, se muestre o se oculte el menú.
Menú .ul-links que contiene los enlaces.
classList.toggle Añade o elimina la clase active en el contenedor del menú para mostrar/ocultar los enlaces.
El evento click en el botón hamburguesa menuToggle activa una función.
Alternar la visibilidad del menú: Con menuLinks.classList.toggle("active"), el menú muestra/oculta los enlaces al agregar o quitar la clase active.

Botón de modo oscuro que permite al usuario alternar entre el modo claro y oscuro. El ícono de la luna representa el modo oscuro, y el ícono del sol representa el modo claro.
En el documento HTML se agregó un botón para alternar entre modos se encuentra dentro de la barra de navegación y tiene un ícono que cambia cuando se cambia el modo.
Para este botón le dimos un id llamado "modo" y una clase "btn-modo" 
Los estilos para los modos claro y oscuro se definen utilizando clases CSS.
El JavaScript maneja la alternancia entre los dos modos y guarda la preferencia del usuario en localStorage. 
También aplicamos DOMContentLoaded para asegura que el código se ejecute después de que el DOM esté completamente cargado.
Función flecha para el evento con addEventListener y llamamos el id con getElementById.
Con .classList agremamos y eliminamos clases para poder darse el efecto si esta claro pasea oscuro y viceversa.
Iconos: Usamos iconos de Font Awesome para darle un toque visual atractivo con los mismos.

Leer Más Este proyecto añade interactividad a un elemento de la galería para mostrar u ocultar texto adicional con un botón "Leer más".
Inicialmente: El texto adicional está oculto.
Interacción: Al hacer clic en el botón, se muestra el texto y el botón cambia a "Leer menos". Al hacer clic nuevamente, el texto se oculta y el botón vuelve a "Leer mas".
