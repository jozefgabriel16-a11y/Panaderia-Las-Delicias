<script lang="ts">
	import "./layout.css";
	import favicon from "$lib/assets/favicon.svg";
	import Icon from "@iconify/svelte";

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav class="flex justify-between items-center px-10 py-3">
	<p class="text-3xl font-extrabold font-serif flex gap-0.5 items-center playfair-display-600">
		<Icon icon="mdi:bakery" width={60} height={60} />
		Panaderia <br> Las Delicias 
	</p>

	<div class="flex gap-3.5 uppercase font-semibold">
		<a class="flex gap-0.5 items-center" href="/">Home</a>
		<a class="flex gap-0.5 items-center" href="/breads">Panes</a>
		<a class="flex gap-0.5 items-center" href="/bakery">Pastelería</a>
		<a class="flex gap-0.5 items-center" href="/breakfast">Desayunos y Cafe</a>
	</div>
 
	<button class="font-extrabold uppercase text-amber-50 px-10 py-2 bg-stone-600 hover:bg-stone-700 transition-colors" >Visit us</button>
</nav>

{@render children()}

<footer style="background-color: #E5E2E1; padding: 20px;" class="flex py-5">


	<div>
	  <p class="text-3xl font-extrabold font-serif flex gap-0.5 items-center playfair-display-600">
		<Icon icon="mdi:bakery" width={60} height={60} />
		Panaderia <br> Las Delicias 
	</p>

		<a href="" class="text-xl"
			> Panaderia tradicional con años de experiencia en el mercado</a
		>
	</div>


	
	<div>
		<p class="text-2xl">Ubicacion y horario</p>

		<a href="">Carabobo, Venezuela</a>

		<a href="">Lunes a Sabado de 6:30 A.M. a 6:00 P.M.</a>
	</div>
</footer>
