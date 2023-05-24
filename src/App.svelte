<script>
	import Header from "./Components/Header.svelte";
	import Meme from "./Components/Meme.svelte"
</script>

<main>
	<Header/>
	<Meme/>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		max-width: 240px;
		margin: 0 auto;
	}


	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}
</style>