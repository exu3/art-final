<script>
    const randInt = Math.floor(Math.random() * 300)
    const lastDigit = randInt % 10
    let suffix = "th";
    if (lastDigit == 1) {
        suffix = "st";
    } else if (lastDigit == 2) {
        suffix = "nd";
    } else if (lastDigit == 3) {
        suffix = "rd";
    } else {
        suffix = "th";
    }
</script>

<footer>
    <p>Congrats, you are the {randInt}{suffix} visitor of this website.</p>
</footer>

<style>
    footer {
        text-align: center;
    }
</style>