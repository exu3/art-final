<script>
	import Footer from "./components/Footer.svelte"
</script>

<main>
	<h1>Digital Art Portfolio</h1>
	<p>Good morning.</p>
	<hr/>
	<div>
		<ul class="nav">
			<li><a href="/projects">Projects</a></li>
			<li><a href="/about">About</a></li>
		</ul>
	</div>
	<hr/>

	<p class="text-center">******** END ********</p>
	<Footer />
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 450px;
		margin: 0 auto;
	}
	h1 {
		text-transform: uppercase;
		font-size:2em;
	}

	.nav {
		display: flex;
		flex-direction: row;
		list-style: none;
		justify-content: space-evenly;
	}

	.text-center {
		text-align: center;
	}
</style>