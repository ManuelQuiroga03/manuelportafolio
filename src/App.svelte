<!-- Portafolio.svelte -->
<script>
	import Navbar from "./Navbar/navbar.svelte";


	export let name;
	name = 'Manuel Hernández Quiroga';
</script>

<main>
	<Navbar></Navbar>
	<!-- <h1>Hola, soy {name}.</h1>
	<p>Soy Ingeniero en Informática especializado en el desarrollo de software.</p>
	<p>Tengo habilidades en desarrollo Frontend y Backend, incluyendo:</p>
	<ul>
		<li>HTML, CSS, JavaScript (y frameworks como React o Vue para Frontend)</li>
		<li>Node.js, Express (para Backend)</li>
		<li>Bases de datos SQL (como MySQL, PostgreSQL)</li>
	</ul>
	<p>Puedes ver más sobre mi trabajo en mi <a href="https://github.com/tuusuario">perfil de GitHub</a>.</p> -->
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 600px;
		margin: 0 auto;
	}

	h1 {
		color: #3366ff;
		font-size: 3em;
		font-weight: 600;
		margin-bottom: 0.5em;
	}

	p {
		font-size: 1.2em;
		line-height: 1.6;
	}

	ul {
		text-align: left;
		margin-left: 2em;
	}

	@media (min-width: 768px) {
		main {
			max-width: 800px;
		}
	}
</style>
