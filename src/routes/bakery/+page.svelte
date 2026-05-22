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

<section>
    <Alfajor precio={5.0} titulo="Alfajor de chocolate" img="/alfajorchocolate.jpg" />
    <Alfajor precio={2.0} titulo="Alfajor de pistacho" img="/alfajor.jpg" />
    <Alfajor precio={3.0} titulo="Alfajor de crema" img="/alfajora.jpg" />
    <Alfajor precio={4.0} titulo="Alfajor de fresa" img="/alfajorb.jpg" />
</section>
