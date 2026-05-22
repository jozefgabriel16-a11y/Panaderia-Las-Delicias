<script>
    const { precio, titulo, img } = $props();
</script>

<div>
    <p>{titulo}</p>
    <p>{precio}$</p>

    <div>
        <img src={img} alt="" />
    </div>
</div>
