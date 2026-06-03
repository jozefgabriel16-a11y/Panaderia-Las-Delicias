<script>
    import Alfajor from "$lib/components/Alfajor.svelte";
</script>

<section>
    <p>La Collection</p>
    <p>Pastelería boutique</p>
    <p>
        A curated symphony off French tradition and modern art with a
        sensasional ingredients
    </p>
</section>

<section class="flex justify-between py-3">
    <Alfajor
        precio={5.0}
        titulo="Alfajor de chocolate"
        img="/alfajorchocolate.jpg"
    />
    <Alfajor precio={2.0} titulo="Alfajor de pistacho" img="/alfajor.jpg" />
    <Alfajor precio={3.0} titulo="Alfajor de crema" img="/alfajora.jpg" />
    <Alfajor precio={4.0} titulo="Alfajor de fresa" img="/alfajorb.jpg" />
</section>

<section class=" py-3">
    <div>
        <p>Tortas</p>
    </div>

    <div class="flex">


        <div class="flex-1">
            <p>torta de chocolate</p>
            <img class="flex flex-2" src="/ch.jpg" alt="" />
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
