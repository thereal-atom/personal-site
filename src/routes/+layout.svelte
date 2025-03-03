<script lang="ts">
    import "../app.css";

	let { children } = $props();
</script>

<div class="relative flex items-center justify-center w-screen h-full min-h-screen bg-[#101010] text-white">
    {@render children()}
</div>