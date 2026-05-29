<script lang="ts">
	import "./layout.css";
	import favicon from "$lib/assets/favicon.svg";
	import Icon from "@iconify/svelte";

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav class="flex justify-between items-center px-10 py-3">
	<p class="text-xl font-extrabold flex gap-0.5 items-center">
		<Icon icon="mdi:bakery" width={60} height={60} />
		Panaderia Las Delicias 
	</p>

	<div class="flex gap-3.5">
		<a class="flex gap-0.5 items-center" href="/">Home</a>
		<a class="flex gap-0.5 items-center" href="/breads">Panes <Icon icon="mdi:bread" /></a>
		<a class="flex gap-0.5 items-center" href="/bakery">Pastelería <Icon icon="mdi:chocolate" /></a>
		<a class="flex gap-0.5 items-center" href="/breakfast">Desayunos <Icon icon="fluent-mdl2:breakfast" /></a>
	</div>
 
	<button class="font-extrabold text-amber-50 px-7 py-1.5 bg-stone-600">Visit us</button>
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
