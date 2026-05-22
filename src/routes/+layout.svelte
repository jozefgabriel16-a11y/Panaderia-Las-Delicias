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

<footer>

<div>
	<p>L'artisan</p>

	<a href="">A boutique bakery dedicated to the preservation of traditional french baking methods and organic ingredients</a>

</div>

<div>
	<p>Explore</p>

	<a href="">conact</a>
	<a href="">opening hours</a>
	<a href="">location</a>
	<a href="">journal</a>

</div>

<div>
	<p>connect</p>

	<a href="">instagram</a>
	<a href="">newsletter</a>

</div>

<div>
	<p>location</p>

	<a href="">Paris,France</a>
	<a href="">tuesday-sunday: 7:00am-18:00pm</a>
	
</div>
</footer>
