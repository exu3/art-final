<script>
	import Greeting from '../lib/Greeting.svelte';
	import List from '../lib/List.svelte';
	import Footer from '../lib/Footer.svelte';
	import Ads from '../lib/Ads.svelte';
</script>

<main>
	<h1>Digital Art Portfolio</h1>
	<Greeting />
	<hr />
	<div>
		<ul class="nav">
			<li><a href="#projects">Projects</a></li>
			<li><a href="/about">About</a></li>
		</ul>
	</div>
	<hr />
	<p>
		Hello. My name is Ella, and I am a senior at Foothill High School. This is my art portfolio for
		Semester 1. <span class="more">Read more...</span>
	</p>
	<List />
	<p class="text-center">******** END ********</p>
	<Footer />
	<hr />
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

	.more {
		color: blue;
		text-decoration: underline;
		text-decoration-style: dotted;
		cursor: pointer;
	}
</style>
