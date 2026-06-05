<script>
    import Alfajor from "$lib/components/Alfajor.svelte";
</script>

<section>
    <p>LA COLECCIÓN</p>
    <p>Pastelería las delicias</p>
    <p>A curated symphony of French tradition and modern artistry. Each piece is hand-crafted daily using the world's finest seasonal ingredients.</p>
</section>

<section class=" py-3 px-5">
    <div class="py-8">
        <p class="items-center text-5xl font-bold text-center">Tortas</p>
    </div>

    <div class="flex gap-16 p-12">
        <div class="flex-2">
            <img class="flex flex-2 w-full h-[740px] object-cover" src="/ch.jpg" alt="" />
            <p class="playfair-display-600 text-5xl">torta de chocolate</p>
            <p>1500bs</p>
        </div>

        <div class="flex-3 space-y-16">
            <div class="flex items-end gap-5">
                <img src="/vai.jpeg" alt="" class="h-48 w-48 object-cover" />
                <div class="flex justify-between flex-1 text-stone-900">
                    <p class="text-2xl playfair-display-600">torta de vainilla</p>
                    <p class="text-lg text-stone-800">1500bs</p>
                </div>
            </div>
            <div class="flex items-end gap-5">
                <img src="/fre.jpg" alt="" class="h-48 w-48 object-cover" />
                <div  class="flex justify-between flex-1 text-stone-900">
                    <p class="text-2xl playfair-display-600">torta de fresa</p>
                    <p class="text-lg text-stone-800">1500bs</p>

                </div>
            </div>
            <div class="flex items-end gap-5">
                <img src="/vai.jpeg" alt="" class="h-48 w-48 object-cover" />
                <div class="flex justify-between flex-1 text-stone-900">
                    <p class="text-2xl playfair-display-600">torta de vainilla</p>
                    <p class="text-lg text-stone-800">1500bs</p>
                </div>
            </div>
        </div>
    </div>
</section>

<section class="flex py-3 px-5 gap-5">
    <Alfajor
        precio={5.0}
        titulo="Alfajor de chocolate"
        img="/alfajorchocolate.jpg"
    />
    <Alfajor precio={2.0} titulo="Alfajor de pistacho" img="/alfajor.jpg" />
    <Alfajor precio={3.0} titulo="Alfajor de crema" img="/alfajora.jpg" />
    <Alfajor precio={4.0} titulo="Alfajor de fresa" img="/alfajorb.jpg" />
</section>

