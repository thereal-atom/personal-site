<script lang="ts">
    import "../app.css";

	let { children } = $props();
</script>

<div class="relative flex items-center justify-center w-screen h-full min-h-screen bg-[#101010] text-white">
    <div
        class="absolute w-screen h-full z-10 pointer-events-none"
        style="background-size: 64px; background-repeat: repeat; background-image: url('/fuzzy.png'); opacity: 0.06;"
    ></div>
    {@render children()}
</div>