<script>
	//import Counter from "$lib/Counter.svelte";

	let count = 0;	

	function CountUp() {
		count += 1;
	}
</script>

<h1>{count}</h1>
<button on:click={CountUp}>{count}</button>

<!-- <Counter />
<Counter /> -->