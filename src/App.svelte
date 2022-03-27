<script>
	export let name;
</script>

<main>
	<header class="header">
		<img src="images/logo.svg" alt="logo" />
		AluraGeek
		<button>Login</button>
		<img src="images/busca.svg" alt="busca" />
	</header>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>