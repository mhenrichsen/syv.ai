<script>
	import Header from './Header.svelte';
	import "../app.css";
	import { onMount } from 'svelte';
	import Footer from './Footer.svelte';

onMount(() => {
  document.documentElement.setAttribute('data-theme', 'cupcake');
});
</script>

<div class="app">
	
	<Header />

	<main>
		<slot />
	</main>

	<Footer />

</div>
