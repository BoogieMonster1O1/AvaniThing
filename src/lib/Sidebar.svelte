<script lang="ts">
    import { page } from '$app/stores';
    import { faHome, faComputer, faEnvelope, faImage } from '@fortawesome/free-solid-svg-icons'
    import Fa from 'svelte-fa'

    const pages = [
        {
            name: 'Home',
            path: '#home',
            icon: faHome,
        },
        {
            name: 'Info',
            path: '#info',
            icon: faComputer
        },
        {
            name: 'Contact',
            path: '#contact',
            icon: faEnvelope
        },
        {
            name: 'Gallery',
            path: '#gallery',
            icon: faImage
        },
    ];

    $: currentPage = $page.url.pathname;
</script>

<div class="top-0 sticky max-sm:hidden h-screen">
    <div class="flex flex-col flex-none mt-8">
        {#each pages as { name, path, icon }}
            <a
                href={path}
                class="
                flex flex-col
                items-center justify-start
                px-4 py-2
                rounded-md transition
                hover:bg-gray-200 dark:hover:bg-neutral-700
                active:bg-gray-400 dark:active:bg-gray-800
                "
                class:active={currentPage === path}
            >
                <span class="mr-2">
                    <Fa icon={icon} size={"3x"}/>
                </span>
                <span>{name}</span>
            </a>
        {/each}
    </div>
</div>
