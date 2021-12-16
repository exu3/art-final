<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Hand Collage</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p>main body here</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/hand_collage/handcollage.jpg?token=ARIDILG42WOM4EJZDNUINWTBYSTC2"
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
