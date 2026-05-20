<script lang="ts">
	import './layout.css';
	import favicon from '$lib/assets/favicon.svg';

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav>
	<p>L'artisan</p>

	<div>
		<a href="/">Home</a>
		<a href="/bakery">Pastelería</a>
		<a href="/breads">Panes</a>
		<a href="/breakfast">Desayunos</a>
	</div>

	<button>Visit us</button>
</nav> 

{@render children()}

Footer
