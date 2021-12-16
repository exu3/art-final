<script>
	import Flavor from '../../lib/Flavor.svelte';
</script>

<main>
	<h1>Photo Illustration</h1>
	<hr />
	<div>
		<a href="/">&larr; Back</a>
	</div>
	<hr />
	<article>
		<p class="copy">
			This piece is combines elements of digital illustration with photos. I outlined the sweatshirt
			and hood as well as a green leafy branch that was visible from the window view. This original
			photo was taken at a <a href="https://codeday.org/ba">CodeDay</a> event.
		</p>
		<img
			src="https://raw.githubusercontent.com/eilla1/art/main/assignments/photo_illustration/photoillustration.jpg?token=ARIDILFGJOVHTNILNEVFCODBYSTN6"
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
