<script>
	import { Button } from "$lib/components/ui/button";
	import '../app.css';
	import Header from './Header.svelte';
</script>

<div class="app">
	<Header />

	<main>
		<Button>Click me</Button>
		<slot />
	</main>

	<footer>
		<p>visit <a href="https://kit.svelte.dev">kit.svelte.dev</a> to learn SvelteKit</p>
	</footer>
</div>


