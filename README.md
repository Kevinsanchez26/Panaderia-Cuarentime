<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<meta http-equiv="X-UA-Compatible" content="ie=edge">
	<link href="https://fonts.googleapis.com/css?family=Open+Sans:400,700&display=swap" rel="stylesheet">
	<script src="https://kit.fontawesome.com/2c36e9b7b1.js"></script>
	<link rel="stylesheet" href="estilos.css">
	<title>Panaderia Cuarentime</title>
</head>
<body>
	
	<div class="contenedor">
		<header>
			<div class="logo">
				<h1>Panaderia Cuarentime</h1>
				<p>Sean Bienvenidos</p>
				<p>Vendemos los panes y dulces mas fresco</p>
			</div>
			<form action="">
				<input type="text" class="barra-busqueda" id="barra-busqueda" placeholder="Buscar">
			</form>
			<div class="categorias" id="categorias">
				<a href="#" class="activo">Todos</a>
				<a href="#">Panes</a>
				<a href="#">Dulces</a>
				<a href="#">Pedidos Especiales</a>
				<a href="#">Pizza</a>
				<a href="#">Contactenos</a>
			</div>
		</header>

		<section class="grid" id="grid">
			<div class="item" 
				 data-categoria="panes"
				 data-etiquetas="Panes baguette"
				 data-descripcion=" Ven y disfruta de nuestro pan baguette."
			>
				<div class="item-contenido">
					<img src="img/Pan baguetee.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="dulces"
				 data-etiquetas="pan dulce kisse"
				 data-descripcion="2.- Ven e invita a tus amigos a a disfrutar de nuestro dulce con kisse."
			>
			
				<div class="item-contenido">
					<img src="img/pan dulce con kisse.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="panes"
				 data-etiquetas="Panes Casero"
				 data-descripcion="Nuestro pan con recetas de casa ven y pruebla te encantara."
			>
				<div class="item-contenido">
					<img src="img/pan casero.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="dulces"
				 data-etiquetas="Dulce navidad"
				 data-descripcion="El mejor dulce de navidad lo tenemos nosotros,  para que compartas una noche magica con tu familiares."
			>
				<div class="item-contenido">
					<img src="img/Dulce navideño.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="dulces"
				 data-etiquetas="Dulce  d dona Dona"
				 data-descripcion="La mejor dona la hacemos nosotros"
			>
				<div class="item-contenido">
					<img src="img/Dona.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="panes"
				 data-etiquetas="panes agua"
				 data-descripcion="No dejes que te lo cuenten,porque se llame pan agua no es agua es uno de nuestros sabrosos panes exportados de España ven y disfrutalo."
			>
				<div class="item-contenido">
					<img src="img/Pan agua.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria="panes"
				 data-etiquetas="pan molde leche"
				 data-descripcion="Pan molde de leche"
			>
				<div class="item-contenido">
					<img src="img/Pan de molde de leche.jpeg" alt="">
				</div>
			</div>

			<div class="item" 
				 data-categoria="panes"
				 data-etiquetas="Pan panito  leche Leche "
				 data-descripcion="Panito de leche"
			>
				<div class="item-contenido">
					<img src="img/Pan de leche.jpeg" alt="">
				</div>
			</div>

			<div class="item"
				 data-categoria=pizza"
				 data-etiquetas="naturaleza hojas plantas"
				 data-descripcion="9.- Lorem ipsum dolor sit amet consectetur.
				 	"
			>
				<div class="item-contenido">
					<img src="img/naturaleza1.png" alt="">
				</div>
			</div>
			<div class="item"
				 data-categoria=pizza"
				 data-etiquetas="naturaleza hojas plantas"
				 data-descripcion="9.- Lorem ipsum dolor sit amet consectetur.
				 	"
			>
				<div class="item-contenido">
					<img src="img/naturaleza1.png" alt="">
				</div>
			</div>
		</section>

		<section class="overlay" id="overlay">
			<div class="contenedor-img">
				<button id="btn-cerrar-popup"><i class="fas fa-times"></i></button>
				<img src="" alt="">
			</div>
			<p class="descripcion"></p>
		</section>

		<footer class="contenedor">
			<div class="redes-sociales">
				<div class="contenedor-icono">
					<a href="" target="_blank" class="twitter">
						<i class="fab fa-twitter"></i>
					</a>
				</div>
				<div class="contenedor-icono">
					<a href="" target="_blank" class="facebook">
						<i class="fab fa-facebook-f"></i>
					</a>
				</div>
				<div class="contenedor-icono">
					<a href="https://www.instagram.com/panaderia_cuarentime/" target="_blank" class="instagram">
						<i class="fab fa-instagram"></i>
					</a>
				</div>
			</div>
			<div class="creado-por">
				<p>Creado por  <a href="#">Kevin Sanchez-Yan Rodrguez-Merith Carpio</a> - <a href="panaderia.html.html">Panaderia Cuarentime</a></p>
			</div>
		</footer>
	</div>

	<script src="https://unpkg.com/web-animations-js@2.3.2/web-animations.min.js"></script>
	<script src="https://unpkg.com/muuri@0.8.0/dist/muuri.min.js"></script>
	<script src="main.js"></script>
</body>
</html>
