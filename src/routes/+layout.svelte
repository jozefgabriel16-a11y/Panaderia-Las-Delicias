<script lang="ts">
	import "./layout.css";
	import favicon from "$lib/assets/favicon.svg";
	import Icon from "@iconify/svelte";

	let { children } = $props();
</script>

<svelte:head><link rel="icon" href={favicon} /></svelte:head>

<nav class="flex items-center px-10 py-3">
	<p
		class="text-3xl font-extrabold font-serif flex gap-0.5 items-center playfair-display-600"
	>
		<Icon icon="mdi:bakery" width={60} height={60} />
		Panaderia <br /> Las Delicias
	</p>

	<div class="flex flex-1 gap-3.5 uppercase font-semibold justify-center items-center text-center">
		<a class="flex gap-0.5 items-center" href="/">Home</a>
		<a class="flex gap-0.5 items-center" href="/breads">Panes</a>
		<a class="flex gap-0.5 items-center" href="/bakery">Pastelería</a>
		<a class="flex gap-0.5 items-center" href="/breakfast"
			>Desayunos y Cafe</a
		>
	</div>
</nav>

{@render children()}

<footer style="background-color: #E5E2E1;" class="flex py-18 ">
	<div>
		<a href="">
			<p
				class="text-3xl font-extrabold font-serif flex gap-0.5 items-center playfair-display-600 px-12"
			>
				<Icon icon="mdi:bakery" width={60} height={60} />
				Panaderia <br /> Las Delicias
			</p>

			<p class="max-w-98 px-12 py-2 text-xl">Panaderia tradicional con años de experiencia en el mercado</p>
		</a>
	</div>

	<div>
		<p class="text-2xl">Ubicacion y horario</p>

		<p>Carabobo, Venezuela</p>
 
	    <p>Lunes a Sabado de 6:30 A.M. a 6:00 P.M.</p>
	</div>

	<div class="px-3">
		<p class="text-2xl ">Como Contactarnos</p>
		<a href="https://api.whatsapp.com/send/?phone=584141456300&text=Buenas, desearia...">Whatsapp</a>
	</div>
</footer>
