<script>
    export let title = '';
    export let items = [];
    export let emoji = '';
</script>

<div class="p-8 bg-gradient-to-br from-gray-900 to-black rounded-xl border border-gray-800 hover:border-[#1DB954] transition-all">
    <h3 class="text-xl font-semibold mb-4">{emoji} {title}</h3>
    <ul class="space-y-3 text-gray-300">
        {#each items as item}
            <li class="flex items-center gap-2">
                <div class="w-1 h-1 bg-[#1DB954] rounded-full"></div>
                {item}
            </li>
        {/each}
    </ul>
</div>