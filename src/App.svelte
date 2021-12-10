<script>
	import Greeting from "./components/Greeting.svelte"
	import About from "./components/About.svelte"
	import List from "./components/List.svelte"
	import Footer from "./components/Footer.svelte"
	import Ads from "./components/Ads.svelte"
</script>

<main>
	<h1>Digital Art Portfolio</h1>
	<Greeting />
	<hr/>
	<div>
		<ul class="nav">
			<li><a href="#projects">Projects</a></li>
			<li><a href="#about">About</a></li>
		</ul>
	</div>
	<hr/>
	<About />
	<List />
	<p class="text-center">******** END ********</p>
	<Footer />
	<hr/>
	<Ads />
</main>

<style>
	main {
		padding: 1em;
		max-width: 450px;
		margin: 0 auto;
	}
	h1 {
		text-transform: uppercase;
		font-size: 1.5em;
		font-family: 'Merchant Copy Wide', 'Merchant Copy';
		text-align: center;
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