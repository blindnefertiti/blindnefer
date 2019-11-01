# blindnefer
<!DOCTYPE html>
<html>
	<head>
		<title> Ejemplo de estructuración </title>
		<meta charset="utf-8">
	</head>
	<body>
		<header id="top">
			<h1>Esto es una cabecera en la sección header</h1>
		</header>
		<nav>
			<header>
				<h1>Esta cabecera no es obligatoria pero sería el título de un menú de navegación</h1>
			</header>
			<ul> <!-- la lista de enlaces del menu de navegación -->
				<li><a href="./index.html" title="Página inicial">Home</a></li>
				<li><a href="./structure.html" title="Página con la información de la estructura">Estructura</a></li>
				<li><a href="./validation.html" title="Página con la información de las validaciones">Validaciones</a></li>
				<li><a href="./browsers.html" title="Detalle de la visualización con diferentes navegadores">Navegadores</a></li>
			</ul>
		</nav>
		<article>
			<header>
				<h1>cabecera del artículo</h1>    
			</header>
			<section>
				<p>Contenido de la sección 1(recordad que se pueden poner headers también aquí)</p>	
			</section>
			<section>
				<div id="columnaIzq"><p>Contenido de la sección 2(que queremos que sea la col izq cuando pongamos CSS)</p>	</div>
				<div id="columnaDer"><p>Contenido de la sección 2(que queremos que sea la col der cuando pongamos CSS)</p>	</div>
			</section>
		</article>
		<aside>
			<p>Algunos datos extras no relacionados con el contenido del artículo</p>
		</aside>
		<footer>
			<p>sección de pié de página (recordad que también se puede poner en las secciones o en los articles)</p>
		</footer>
	</body>
