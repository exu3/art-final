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
		<p class="copy">
			This project was an exercise for using layers, clipping masks, and selection & transform
			techniques. It features a stock photo of hands and other free images from the internet. The
			background is an illustration of Monument Valley from the <a
				href="https://hack.af/zephyr"
				target="_blank">Hacker Zephyr</a
			> open source repository.
		</p>
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
		width: 100%;
		margin: 0 auto;
	}
</style>
