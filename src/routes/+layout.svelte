<script lang="ts">
	import "./layout.css";
	import favicon from "$lib/assets/favicon.svg";
	import Icon from "@iconify/svelte";

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav>
	<p><Icon icon="mdi:bakery" width={60} height={60} />L'artisan</p>

	<div>
		<a href="/">Home</a>
		<a href="/breads">Panes <Icon icon="mdi:bread" /></a>
		<a href="/bakery">Pastelería <Icon icon="mdi:chocolate" /></a>
		<a href="/breakfast">Desayunos <Icon icon="fluent-mdl2:breakfast" /></a>
	</div>

	<button>Visit us</button>
</nav>

{@render children()}

<footer>
	<div>
		<p>L'artisan</p>

		<a href=""
			>A boutique bakery dedicated to the preservation of traditional
			french baking methods and organic ingredients</a
		>
	</div>

	<div>
		<p>Explore</p>

		<a href="">contact</a>
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
