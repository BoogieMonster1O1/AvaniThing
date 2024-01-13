<script>
    import Sidebar from "$lib/Sidebar.svelte";
import "../app.css"
</script>

<svelte:head>
    <title>Nagaraj GS</title>
</svelte:head>

<div class="flex flex-row dark:bg-black bg-slate-300 min-h-screen dark:text-white text-black">
    <Sidebar />

    <div class="flex flex-1 flex-col justify-center" id="home">
        <slot />
    </div>
</div>
