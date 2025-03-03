<svelte:head>
    <title>Oscar | Projects | Obsidian Notes AI</title>
</svelte:head>

<div class="flex flex-col h-full min-h-screen w-full mt-16 px-64 max-2xl:px-48 max-xl:px-8 max-md:px-0">
    <h1 class="text-3xl font-bold max-md:text-2xl">Obsidian Notes AI</h1>
	<div
		class="mt-8 flex flex-col rounded-[32px] border border-white border-opacity-5 bg-[#161616] p-8"
	>
        <p class="mt-4">I build this project to learn how to use generative AI APIs, and practice my Next.js and tRPC skills.</p>
        <p class="mt-4">It's built with Next.js, tRPC and Tailwind via the create t3 template which was a very smooth experience. I am using the Google Gemini SDK and the Gemini 2.0 flash as well as text embedding models.</p>
        <p class="mt-8">You can upload your markdown files (mine come from obsidian), and ask the LLM questions about your notes.</p>
        <p class="mt-4">It'll reference your notes if it used them for it's response. Conversations are saved and chat history is applied to prompts.</p>
        <img
            class="my-8 border-4 border-white/20 rounded-md"
            src="/examples/obsidian-notes-ai.png"
            alt="obsidian-notes-ai"
        />
		<div class="mt-4 flex flex-col">
			<h2 class="text-2xl font-semibold max-md:text-xl">Stack</h2>
			<div class="mt-2 flex flex-row flex-wrap">
				<div class="project-technology-container">
					<img class="project-technology-icon" src="/skills/typescript.svg" alt="typescript" />
					<p class="project-technology-text">Typescript</p>
				</div>
				<div class="project-technology-container">
					<img class="project-technology-icon" src="/skills/nextjs.svg" alt="nextjs" />
					<p class="project-technology-text">Next.js</p>
				</div>
				<div class="project-technology-container">
					<img class="project-technology-icon" src="/skills/trpc.svg" alt="trpc" />
					<p class="project-technology-text">tRPC</p>
				</div>
				<div class="project-technology-container">
					<img class="project-technology-icon" src="/skills/supabase.svg" alt="supabase" />
					<p class="project-technology-text">Supabase</p>
				</div>
				<div class="project-technology-container">
					<img class="project-technology-icon" src="/skills/tailwindcss.svg" alt="tailwind" />
					<p class="project-technology-text">Tailwind</p>
				</div>
			</div>
		</div>
	</div>
	<h2 class="mt-8 text-2xl font-semibold max-md:text-xl">What I learned</h2>
	<div
		class="mt-8 flex flex-col rounded-[32px] border border-white border-opacity-5 bg-[#161616] p-8"
	>
		<div class="flex flex-col">
			<p>During this project I learned a lot about the more practical aspects of generative AI.</p>
            <p class="mt-4">I knew of things like RAG and prompt engineering but this put it in am much clearer picture for me in how it's actually implemented.</p>
            <p class="mt-4">I use text embeddings to find the relevant notes to provide as context to the LLM which was really interesting to learn.</p>
            <p class="mt-4">I also used Next.js and tRPC for this project (opposed to my usual SvelteKit and elysia), which refreshed my knowledge (I used to main tRPC ~2 years, and nextjs/react almost 4 years ago). I always found nextjs unnecessarily tricky to work with, unlike SvelteKit, but using it in depth taught me some better practices and conventions which made the experience more enjoyable. I also forgot how great tRPC was to use. The type safety works super well and makes for a great DX.</p>
            <p class="mt-4">One thing I struggled with was streaming text from the LLM, via my tRPC backend to my frontend. I am still looking for a relatively simple way to do this.</p>
        </div>
	</div>
</div>

<style lang="postcss">
	.project-technology-container {
		@apply mb-2 mr-2 mt-4 flex h-fit flex-row items-center rounded-[4px] border border-white border-opacity-5 bg-[#242424] p-2 max-md:py-1.5;
	}

	.project-technology-icon {
		@apply h-6 w-6 max-md:h-4 max-md:w-4;
	}

	.project-technology-text {
		@apply ml-2 text-sm font-bold max-md:text-xs;
	}
</style>
