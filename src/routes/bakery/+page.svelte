<script>
    import Alfajor from "$lib/components/Alfajor.svelte";
</script>

<section class="py-5 flex-col md:flex-row">
    <p class="flex justify-center text-lg playfair-display-600">LA COLECCIÓN</p>
    <p class="flex justify-center text-7xl playfair-display-600">
        Pastelería las delicias
    </p>
    <p class="flex justify-center text-3xl py-5 px-5 text-center max-w-xl m-auto">
        A curated symphony of French tradition and modern artistry. Each piece
        is hand-crafted daily using the world's finest seasonal ingredients.
    </p>
</section>

<section class=" py-3 px-5">
    <div class="py-8">
        <p class="items-center text-5xl font-bold text-center playfair-display-600">Tortas</p>
    </div>

    <div class="flex gap-16 p-12">
        <div class="flex-2">
            <img
                class="flex flex-2 w-full h-[690px] object-cover"
                src="tortah.jpg"
                alt=""
            />
            <div class="flex justify-between">
            <p class="playfair-display-600 text-5xl">torta de chocolate</p>
            <p class="text-lg text-stone-800 py-3">2.5$</p>
            </div>
        </div>

        <div class="flex-3 space-y-16">
            <div class="flex items-end gap-5">
                <img src="/vai.jpeg" alt="" class="h-48 w-48 object-cover" />
                <div class="flex justify-between flex-1 text-stone-900">
                    <p class="text-2xl playfair-display-600">
                        torta de vainilla
                    </p>
                    <p class="text-lg text-stone-800">2.5$</p>
                </div>
            </div>
            <div class="flex items-end gap-5">
                <img src="/fre.jpg" alt="" class="h-48 w-48 object-cover" />
                <div class="flex justify-between flex-1 text-stone-900">
                    <p class="text-2xl playfair-display-600">torta de fresa</p>
                    <p class="text-lg text-stone-800">2.5$</p>
                </div>
            </div>
            <div class="flex items-end gap-5">
                <img src="/vai.jpeg" alt="" class="h-48 w-48 object-cover" />
                <div class="flex justify-between flex-1 text-stone-900">
                    <p class="text-2xl playfair-display-600">
                        torta de vainilla
                    </p>
                    <p class="text-lg text-stone-800">2.5$</p>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="flex py-12 px-16 gap-5">
    <Alfajor
        precio={5.0}
        titulo="Alfajor de chocolate"
        img="/alfajorchocolate.jpg"
    />
    <Alfajor precio={2.0} titulo="Alfajor de pistacho" img="/alfajor.jpg" />
    <Alfajor precio={3.0} titulo="Alfajor de crema" img="/alfajora.jpg" />
    <Alfajor precio={4.0} titulo="Alfajor de fresa" img="/alfajorb.jpg" />
</section>
