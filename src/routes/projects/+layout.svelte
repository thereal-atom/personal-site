<script>
    import { page } from "$app/stores";
</script>

<div class="flex flex-col p-8 w-screen">
    <div class="flex flex-row">
        <a
            class="w-fit px-4 py-2 font-bold bg-[#111111] border border-white border-opacity-5 rounded-md"
            href="/"
        >
            Home
        </a>
        <a
            class="w-fit ml-4 px-4 py-2 font-bold bg-[#111111] border border-white border-opacity-5 rounded-md"
            href="/projects"
        >
            Projects
        </a>
    </div>
    <slot />
</div>