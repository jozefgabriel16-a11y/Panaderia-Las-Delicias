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
    <div>
        <p class="items-center text-5xl font-bold ">Tortas</p>
    </div>

    <div class="flex">
        <div class="flex-1">
            <p>torta de chocolate</p>
            <img class="flex flex-2 w-full h-full object-cover" src="/ch.jpg" alt="" />
            <p>1500bs</p>
        </div>

        <div class="flex-1">
            <div>
                <p>torta de vainilla</p>
                <img src="/vai.jpeg" alt="" />
                <p>1500bs</p>
            </div>
            <div>
                <p>torta de fresa</p>
                <img src="/fre.jpg" alt="" />
                <p>1500bs</p>
            </div>
        </div>
    </div>
</section>
