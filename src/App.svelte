<script>
	export let name;
	export let age;

	const increaseAge = () => {
		age ++;
	}
</script>

<style>
	h1 {
		color: purple;
	}
</style>

<h1>Hello i'm {name}, my age is {age}!</h1>
<button on:click={increaseAge}>Change age</button>
