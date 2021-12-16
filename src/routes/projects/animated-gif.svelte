<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Animated GIF</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p>main body here</p>
		<img
			src="https://user-images.githubusercontent.com/72365100/146412875-44a6100e-a981-45fd-9e39-39647edcf505.gif"
			alt="hi"
		/>
	</article>
	<hr />
	<p class="text-center">******** END ********</p>
	<hr />
	<Flavor />
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

	img {
		width: 450px;
		margin: 0 auto;
	}
</style>
