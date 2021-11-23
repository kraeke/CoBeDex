<script>
    export let pokeman;
</script>
<a class="transition-all duration-300 grid justify-center bg-gray-400 rounded-md m-3 p-8 text-center hover:shadow-lg" href={`/pokemon/${pokeman.id}`}>
    <img class="w-40 h-40" src={pokeman.image} alt={pokeman.name}>
    <h2 class="text-2xl uppercase">{pokeman.id}. {pokeman.name}</h2>
</a>