# miteris-llmm-2-1Para esta actividad he realizado las siguientes vistas:

- index.html - El escaparate de la tienda.
	
	En ella aparece un encabezado con tres partes:
		- Un menú con las opciones que no son estrictamente comerciales (idioma, ayuda, cuenta personal, login y registro)
		- Un acceso al carro de la compra y un cuadro de búsqueda
		- Accesos a los distintos departamentos de la tienda.
	Una sección con dos promociones resaltadas.
	Unos accesos a ofertas por departamentos (búsquedas).
	Un listado de productos en promoción que se pueden añadir a la cesta en el momento.
	Un pie de página con enlaces informativos, contacto y redes sociales.
	
	El carrito de la compra está en un aside oculto que se revelaría al hacer click en el botón "ver compra" del encabezado.
	
	El comportamiento responsive al estrechar la vista hace que los accesos a los departamentos se conviertan en un menú
	en columna oculto que se maneja con un botón de hamburguesa. De modo similar el menú superior es reemplazado por un
	icono que apunta a la página de detalles de usuario.
	Otros efectos de estrechar la vista son el cambiar el número de productos mostrados por filas. Abreviar el texto de
	alguna etiqueta. O cambiar el orden de elementos del encabezado.

- departamentos.html - Es la página principal de la aplicación. Se basa en mostrar consultas a la bd de la tienda.
	
	El encabezamiento es similar al de index.html. Pero se cambian los accesos a los departamentos por unos breadcrumbs
	para la navegación. Al tiempo que el botón hamburguesa pasa a mostrar la columna de búsqueda.
	
	Esta columna de búsqueda tiene un índice jerárquico de los distintos departamentos y unos selectores para refinar
	las consultas que luego se muestran en la zona principal de la página.
	
	La zona principal, tiene dos zonas superiores para seguir mostrando ofertas (una de ellas se esconde luego al reducir
	el ancho) y una inferior en la que se muestra el resultado de la consulta.
	Esta última tiene un desplegable para elegir su	ordenación y controles de navegación bajo el listado de productos.
	Cada producto tiene controles para añadirse a la cesta, todas las imágenes de productos enlazan a su página de detalle.

- producto.html - Es la página que muestra el detalle de los productos.
	
	Encabezamiento y columna lateral se mantienen igual. Pero en la zona principal se muestran los datos ampliados de un
	solo producto. Manteniendo la opción de añadir ese producto al carro.

- info.html - Es una plantilla genérica para dar información al usuario.
	
	Se elimina la navegación por departamentos y el menú hamburguesa.

- user.html - Es una página similar a la de info.html pero con información de usuario.

- registro.html - Es una página con un formulario para dar de alta usuarios.

- login.html - Es una página con un formulario para hacer el login del usuario.
