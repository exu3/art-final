<main>
	<img
		src="/e.png"
		alt="Black ball with letter E in front and center"
		style="margin: 0 auto; text-align: center; display: block; width: 70px"
	/>
	<slot />
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
