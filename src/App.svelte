<!-- Portafolio.svelte -->
<script>
	import Navbar from "./Navbar/navbar.svelte";
	import Footer from "./Footer/footer.svelte";

	export let name;
	name = 'Manuel Hernández Quiroga';
</script>

<div class="contenedor">
	<div class="">
		<Navbar></Navbar>
	</div>
	
	<div class="contentMe">
		<div class="heroMe">
			<div>
				<img class="imgName_CustomImage" src="images/imgPerfil.JPG" alt="Manuel Quiroga">
			</div>
		</div>
		<div class="nameMe">
			<h1>
				<span style="color: #243746;">Manuel</span> <span style="color: gray;">Quiroga</span>
			</h1>
		</div>
		<div class="infoMe mt-4 mb-4">
			<p>Desarrollador Jr en Ximplify</p>
			<p>"El software es un gran combinador; te permite combinar tus ideas con la capacidad de la máquina y ver los resultados de inmediato". - Hal Abelson</p>
			<p></p>
		</div>
		<div class="">
			<div class="text-center mt-4 mb-4">
				<span>Mis Proyectos</span>
			</div>
			<div class="grid-container mt-4 mb-4 ps-4 pe-4">
				<!-- Tarjeta 1 -->
				<div class="card">
					<img src="ruta/a/imagen-proyecto-1.jpg" alt="Proyecto 1">
					<h3>Título del Proyecto 1</h3>
					<p>Descripción breve del Proyecto 1.</p>
				</div>
				<div class="card">
					<img src="ruta/a/imagen-proyecto-1.jpg" alt="Proyecto 1">
					<h3>Título del Proyecto 1</h3>
					<p>Descripción breve del Proyecto 1.</p>
				</div>
				<div class="card">
					<img src="ruta/a/imagen-proyecto-1.jpg" alt="Proyecto 1">
					<h3>Título del Proyecto 1</h3>
					<p>Descripción breve del Proyecto 1.</p>
				</div>
				
			
				<!-- Tarjeta 2 -->
				<div class="card">
					<img src="ruta/a/imagen-proyecto-2.jpg" alt="Proyecto 2">
					<h3>Título del Proyecto 2</h3>
					<p>Descripción breve del Proyecto 2.</p>
				</div>
			
				<!-- ... Repite este bloque para cada tarjeta -->
			</div>
		</div>
	</div>

	<div class="">
		<Footer></Footer>
	</div>
</div>

<style>
	.contenedor{
		margin: 0;
		display: flex;
		flex-direction: column;
		
	}
	.container{
		margin: 0;
		padding: 0;
	}
	.heroMe{
		text-align: center;
		margin-top: 20px;
	}
	.imgName_CustomImage{
        border-radius: 50%;
        width: 150px;
        height: 150px;
        object-fit: contain;
    }
	.nameMe{
		text-align: center;
		margin-top: 30px;
	}
	h1{
		font-size: 50px;
		font-weight: 700;
	}
	.infoMe{
		text-align: center;
		font-size: 25px;
		font-weight: 600;
		margin-left: 15px;
		margin-right: 15px;
	}
	.contentMe{
		padding-left: 0.5rem;
		padding-right: 0.5rem;
	}
	.grid-container {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
		grid-auto-rows: minmax(200px, auto);
        gap: 20px;
        /* Otros estilos del grid */
    }
    .card {
        /* Estilos de la tarjeta */
        border: 1px solid #ccc;
        border-radius: 8px;
        padding: 20px;
    }
    .card img {
        width: 100%; /* Ajusta el tamaño de la imagen */
        border-radius: 8px; /* Bordes redondeados para la imagen */
        margin-bottom: 15px; /* Espaciado entre la imagen y el texto */
    }
</style>
