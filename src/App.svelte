<script>
	export let name;
</script>

<main>
	<header class="header">
		<div class="logo">
			<h1>
				<a href="_blank">
					<img src="images/logo.svg" alt="logo" />
				</a>
			</h1>
		</div>
		<a class="login-button" href="#">Login</a>
		<img src="images/busca.svg" alt="busca" />
	</header>
</main>

<style>
	header {
		display: flex;
    justify-content: space-between;
		align-items: center;
    padding: 16px;
		gap: 2rem;
	}

	.logo h1 {
		margin: 0;
		font-size: 1.5em;
    width: 100px;
	}

	.logo a {
		display: flex;
	}

	.logo img {
		width: 100%;
	}

	.login-button {
		padding: 0.75rem 1rem;
    flex-grow: 1;
    border: 1px solid #2A7AE4;
    background-color: transparent;
		margin-bottom: 0;
		color: #2A7AE4;
		font-family: 'Raleway', sans-serif;
		font-weight: 600;
		font-size: 0.875rem;
		line-height: 1rem;
		font-style: normal;
		text-align: center;
	}
</style>