<!-- Portafolio.svelte -->
<script>
	import Navbar from "./Navbar/navbar.svelte";


	export let name;
	name = 'Manuel Hernández Quiroga';
</script>

<main>
	<Navbar></Navbar>
	
	<h1>Hello {name}!</h1>
	<p>Visit the <a href="https://svelte.dev/tutorial">Svelte tutorial</a> to learn how to build Svelte apps.</p>
	<span>
		<i class="fa-regular fa-user"></i>
	</span>
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
