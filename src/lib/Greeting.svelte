<script>
	let date = new Date();
	let hour = new Date().getHours(); // subtract 8 for GMT - 8 (PST)
	let message;
	if (hour >= 20 && hour <= 4) {
		message = 'Greetings, Mortal. The night is young.';
	} else if (hour >= 5 && hour <= 11) {
		message = 'Good morning.';
	} else if (hour >= 12 && hour <= 16) {
		message = 'Good afternoon.';
	} else if (hour >= 17 && hour <= 19) {
		message = 'Good evening.';
	} else {
		message = 'Good day.';
	}
</script>

<div>
	<p>{date}</p>
	<p>{message}</p>
</div>

<style>
	div {
		text-align: center;
	}
	p {
		font-size: 1em;
	}
</style>
