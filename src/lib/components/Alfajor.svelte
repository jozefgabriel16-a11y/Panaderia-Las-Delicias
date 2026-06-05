<script>
    const { precio, titulo, img } = $props();

    const usuario = {
     
    }
</script>

<div class="flex-1 text-xl ">
 <div class="flex justify-between py-3 font-semibold">
    <p>{titulo}</p>
    <p class="text-gray-500">{precio}$</p>
 </div>
    <div class=" h-96">
        <img src={img} alt="" class=" w-full h-full object-cover"/>
    </div>
</div>
