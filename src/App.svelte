<script lang="ts">
	import Hello from "./Hello.svelte";
import name from "./Hello.svelte"
	// export let name = "gander";
</script>

<main>
	<!-- <h1>Hello {name}!</h1> -->
	<Hello name={"jones"}/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}

	h1 {
		color: #ff3e00;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>