# P-gina-de-ventas-
Estructura de pagina de ventas 
<!DOCTYPE html> #Esta línea indica que este es un documento HTML.
<html> #Esto indica que todo el código HTML se encuentra dentro de esta etiqueta.
<head> #La sección head contiene información sobre la página, incluyendo el título de la página, la codificación de caracteres, el tamaño de la pantalla y la hoja de estilo.
	<title>Tienda en línea</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link rel="stylesheet" href="estilos.css">
</head>
<body> # Este es el cuerpo de la página.
	<header> #La sección header contiene el encabezado de la página, que incluye el título y una lista de navegación.
		<h1>Tienda en línea</h1>
		<nav>
			<ul>
				<li><a href="#">Inicio</a></li>
				<li><a href="#">Productos</a></li>
				<li><a href="#">Contacto</a></li>
			</ul>
		</nav>
	</header>
	<main> #La sección principal de la página contiene dos elementos, un section que muestra los productos destacados y un aside que muestra las categorías.
		<section>
			<h2>Productos destacados</h2>
			<ul>
				<li>
					<img src="img/producto1.jpg" alt="Imagen del producto 1">
					<h3>Producto 1</h3>
					<p>Descripción del producto 1</p>
					<button>Comprar</button>
				</li>
				<li>
					<img src="img/producto2.jpg" alt="Imagen del producto 2">
					<h3>Producto 2</h3>
					<p>Descripción del producto 2</p>
					<button>Comprar</button>
				</li>
				<li>
					<img src="img/producto3.jpg" alt="Imagen del producto 3">
					<h3>Producto 3</h3>
					<p>Descripción del producto 3</p>
					<button>Comprar</button>
				</li>
			</ul>
		</section>
		<aside>
			<h2>Categorías</h2>
			<ul>
				<li><a href="#">Categoría 1</a></li>
				<li><a href="#">Categoría 2</a></li>
				<li><a href="#">Categoría 3</a></li>
			</ul>
		</aside>
	</main>
	<footer> #La sección footer muestra el pie de página con los derechos reservados y el año de la tienda en línea.
		<p>Derechos reservados &copy; 2023 Tienda en línea</p>
	</footer>
</body>
</html>
