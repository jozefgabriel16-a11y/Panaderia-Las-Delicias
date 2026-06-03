<script>
    import Alfajor from "$lib/components/Alfajor.svelte";
</script>


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

<section class=" py-3 px-5">
    <div class="py-8">
        <p class="items-center text-5xl font-bold text-center">Tortas</p>
    </div>

    <div class="flex gap-20 p-12">
        <div class="flex-2">
            <p>torta de chocolate</p>
            <img class="flex flex-2 w-full h-[1024px] object-cover" src="/ch.jpg" alt="" />
            <p>1500bs</p>
        </div>

        <div class="flex-3">
            <div class="flex items-end gap-5">
                <img src="/vai.jpeg" alt="" class="h-48 w-48 object-cover" />
                <div class="flex justify-between flex-1">
                    <p class="text-xl">torta de vainilla</p>
                    <p>1500bs</p>
                </div>
            </div>
            <div>
                <p>torta de fresa</p>
                <img src="/fre.jpg" alt="" class="h-48 w-48 object-cover" />
                <p>1500bs</p>
            </div>
        </div>
    </div>
</section>
