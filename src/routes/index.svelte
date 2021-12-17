<script>
	import Greeting from '../lib/Greeting.svelte';
	import List from '../lib/List.svelte';
	import Footer from '../lib/Footer.svelte';
	import Tooltip from '../lib/Tooltip.svelte';
	import Trex from '../lib/Trex.svelte';
</script>

<main>
	<h1>Digital Art Portfolio</h1>
	<Greeting />
	<hr />
	<div>
		<ul class="nav">
			<li><a href="/about">About</a></li>
			<li><a href="https://github.com/eilla1" target="_blank">GitHub</a></li>
			<li>
				<Tooltip title="uwu, What's this?"
					><a href="https://uwu.boats/important" target="_blank">???</a></Tooltip
				>
			</li>
		</ul>
	</div>
	<hr />
	<p class="copy">
		Hello. My name is Ella, and this is my digital art portfolio. It features various projects I
		worked on this semester (Fall 2021). Like what you see or want to work with me? You can reach me
		via carrier pigeon or email to "hi&nbsp;[at]&nbsp;ella.cx".
	</p>
	<section id="projects">
		<List />
	</section>
	<p class="text-center">******** END ********</p>
	<Footer />
	<hr />
	<Trex />
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
</style>
