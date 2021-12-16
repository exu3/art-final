<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Color Formula Character</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This was a project designed to explore various types of colour schemes and the messages they
			convey. For this project, I used a complementary color scheme. This also reflects the spirit
			of Halloween, hence the broom stick and witch hat.
		</p>
		<img
			src="https://user-images.githubusercontent.com/72365100/146421645-6b00e5ff-5721-44e0-a341-78d7a3858076.png"
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
