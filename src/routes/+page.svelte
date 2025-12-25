<script>
	import constants from '$lib/constants';
</script>

<div
	class="pointer-events-none absolute z-10 h-full w-screen"
	style="background-size: 64px; background-repeat: repeat; background-image: url('/fuzzy.png'); opacity: 0.06;"
></div>
<div
	class="flex h-[900px] w-full flex-row items-center justify-between p-8 max-xl:h-full max-xl:flex-col max-sm:p-4 xl:h-screen"
>
	<div class="flex h-full w-[74.5%] flex-col justify-between max-xl:w-full">
		<div class="flex h-[34%] w-full flex-row justify-between max-xl:h-[250px] max-md:h-auto">
			<div class="box relative aspect-square h-full w-auto max-md:hidden">
				<img
					class="h-full w-full rounded-[32px] object-cover opacity-80 transition-opacity hover:opacity-100"
					src="/oscar.jpg"
					alt="oscar"
				/>
			</div>
			<div class="box mx-4 flex h-full w-full flex-col p-8 max-xl:mr-0 max-md:mx-0 max-sm:p-6">
				<h1 class="text-3xl font-semibold max-sm:text-2xl">Oscar Falemara</h1>
				<span
					class="mt-1 w-fit rounded-md border border-white border-opacity-5 bg-[#242424] px-2 py-1 text-xs font-medium"
					>🚀 Open to Opportunities</span
				>
				<p class="mt-8 text-[#DADDE7] max-2xl:mt-4 max-sm:text-sm">
					I'm a self-taught <span class="font-medium underline">full stack web developer</span> from
					<span
						class="text-nowrap rounded-md border border-white border-opacity-5 bg-[#242424] py-0.5 pl-1 pr-1.5 font-medium"
						>📍London</span
					> with 5+ years of experience.
				</p>
				<p class="mt-4 text-[#DADDE7] max-sm:text-sm">
					I am currently working as a full-stack software engineer at <a
						href="https://coloop.ai"
						class="text-blue-400">Coloop AI</a
					>.
				</p>
			</div>
			<div class="box aspect-square h-full w-auto max-xl:hidden">
				<img
					class="h-full min-h-full w-auto min-w-full rounded-[32px] object-cover opacity-80 transition-opacity hover:opacity-100"
					src="/sunrise.webp"
					alt="sunrise"
				/>
			</div>
		</div>
		<div class="flex h-[64.75%] flex-col justify-between max-xl:flex max-xl:flex-col-reverse">
			<div
				class="flex h-[47%] flex-row justify-between max-xl:mt-4 max-xl:h-[200px] max-md:mt-0 max-md:h-full max-md:flex-col"
			>
				<div
					class="box relative h-full w-[49.5%] overflow-hidden max-md:mt-4 max-md:h-[250px] max-md:w-full max-sm:h-[200px] max-xs:h-[160px]"
				>
					<img
						class="absolute -top-8 opacity-60 transition-all hover:scale-105 hover:opacity-100 max-2xl:static max-2xl:h-full max-2xl:min-h-full max-2xl:w-auto max-2xl:min-w-full max-2xl:object-cover"
						src="/cribgoch.webp"
						alt="cribgoch"
					/>
					<p
						class="absolute right-6 top-6 rounded-md border border-white border-opacity-5 bg-[#242424] py-2 pl-2.5 pr-3 text-xs"
					>
						🏔️ I also like climbing mountains
					</p>
					<p class="absolute bottom-4 left-8 text-[8px]">Crib Goch, Wales</p>
				</div>
				<div
					class="box relative h-full w-[49.5%] overflow-hidden max-md:mt-4 max-md:h-[250px] max-md:w-full max-sm:h-[200px] max-xs:h-[160px]"
				>
					<img
						class="absolute -top-4 opacity-60 transition-all hover:scale-105 hover:opacity-100 max-2xl:static max-2xl:h-full max-2xl:min-h-full max-2xl:w-auto max-2xl:min-w-full max-2xl:object-cover"
						src="/corfu.webp"
						alt="corfu"
					/>
					<p
						class="absolute right-6 top-6 rounded-md border border-white border-opacity-5 bg-[#242424] py-2 pl-2.5 pr-3 text-xs"
					>
						📷 And I like photography
					</p>
					<p class="absolute bottom-4 left-8 text-[8px]">Corfu, Greece</p>
				</div>
			</div>
			<div
				class="flex h-[51%] flex-row justify-between max-xl:mt-4 max-xl:h-[270px] max-xl:flex-row-reverse max-md:h-full max-md:w-full max-md:flex-col-reverse"
			>
				<div
					class="grid aspect-square h-full w-auto grid-cols-2 gap-4 max-xl:ml-4 max-md:ml-0 max-md:mt-4 max-md:flex max-md:aspect-auto max-md:h-auto max-md:w-full max-md:grid-cols-4 max-md:flex-row max-xs:gap-2"
				>
					<a
						class="box-custom-bg aspect-square h-full w-auto bg-[#151515] p-9 transition-all hover:bg-black max-md:h-auto max-md:w-full max-md:p-5"
						href={constants.socials.x.url}
						target="_blank"
					>
						<img class="h-full w-full" src="/socials/x.svg" alt="x" />
					</a>
					<a
						class="box-custom-bg aspect-square h-full w-auto bg-[#151515] p-9 transition-all hover:bg-[#24292e] max-md:h-auto max-md:w-full max-md:p-5"
						href={constants.socials.github.url}
						target="_blank"
					>
						<img class="h-full w-full" src="/socials/github.svg" alt="github" />
					</a>
					<a
						class="box-custom-bg aspect-square h-full w-auto bg-[#151515] p-9 transition-all hover:bg-[#0a66c2] max-md:h-auto max-md:w-full max-md:p-5"
						href={constants.socials.linkedin.url}
						target="_blank"
					>
						<img class="h-full w-full" src="/socials/linkedin.svg" alt="linkedin" />
					</a>
					<a
						class="box-custom-bg aspect-square h-full w-auto bg-[#151515] p-9 transition-all hover:bg-[#c71610] max-md:h-auto max-md:w-full max-md:p-5"
						href={constants.socials.email.url}
						target="_blank"
					>
						<img class="h-full w-full" src="/socials/email.svg" alt="email" />
					</a>
				</div>
				<div
					class="box ml-4 flex h-full w-full flex-col overflow-hidden p-8 max-xl:ml-0 max-xl:py-6 max-md:px-6 max-md:py-4"
				>
					<h1 class="text-3xl font-semibold max-md:text-xl">Skills</h1>
					<div
						class="mt-8 flex w-full flex-row flex-wrap overflow-hidden max-xl:mt-4 max-xl:grid-cols-4 max-md:mt-2"
					>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/typescript.svg" alt="typescript" />
							<p class="skill-text">Typescript</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/nextjs.svg" alt="typescript" />
							<p class="skill-text">Next</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/sveltekit.svg" alt="sveltekit" />
							<p class="skill-text">SvelteKit</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/bun.svg" alt="nodejs" />
							<p class="skill-text">Bun</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/rust.svg" alt="rust" />
							<p class="skill-text">Rust</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/tailwindcss.svg" alt="tailwindcss" />
							<p class="skill-text">Tailwind</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/python.svg" alt="python" />
							<p class="skill-text">Python</p>
						</div>
						<div class="max-md:hidden">
							<div class="skill-container">
								<img class="skill-icon" src="/skills/react.svg" alt="react" />
								<p class="skill-text">React</p>
							</div>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/express.svg" alt="express" />
							<p class="skill-text">express.js</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/aws.svg" alt="express" />
							<p class="skill-text">AWS</p>
						</div>
						<div class="skill-container">
							<img class="skill-icon" src="/skills/trpc.svg" alt="express" />
							<p class="skill-text">tRPC</p>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
	<div
		class="flex h-full w-[24.5%] flex-col justify-between max-xl:mt-4 max-xl:h-full max-xl:w-full"
	>
		<a class="text-3xl font-semibold max-sm:text-2xl" href="/projects">
			Projects <span class="text-xs font-medium text-blue-400">View All Projects</span>
		</a>

		<div class="box flex h-[45%] w-full flex-col p-8 max-xl:mt-4 max-xl:h-full">
			<div class="flex h-full flex-col">
				<div class="flex flex-row items-center">
					<img class="h-8 w-8 rounded-md" src="/projects/coloop.jpeg" alt="exp" />
					<h1 class="ml-3 text-[28px] font-semibold max-sm:text-2xl">Coloop</h1>
				</div>
				<div class="mt-2 flex flex-col">
					<p class="text-xs text-[#DADDE7]">
						Coloop is an AI-Powered Qualitative Research Platform
					</p>
					<p class="mt-2 text-sm text-[#DADDE7]">
						I built many features across the stack including our AI agents, automatic correction and
						postprocessing, agentic transcript parsing, refactored the platform into a multi
						language system and more.
					</p>
					<div class="mt-4 flex flex-col">
						<h2 class="text-xl font-medium">Stack</h2>
						<div class="mt-2 flex flex-row flex-wrap">
							<div class="project-technology-container">
								<img
									class="project-technology-icon"
									src="/skills/typescript.svg"
									alt="typescript"
								/>
								<p class="project-technology-text">Typescript</p>
							</div>
							<div class="project-technology-container">
								<img class="project-technology-icon" src="/skills/nextjs.svg" alt="nextjs" />
								<p class="project-technology-text">Next.js</p>
							</div>
							<div class="project-technology-container">
								<img class="project-technology-icon" src="/skills/aws.svg" alt="aws" />
								<p class="project-technology-text">AWS</p>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="flex w-full flex-row justify-end">
				<a
					class="w-fit rounded-md border border-white border-opacity-5 bg-[#111111] px-4 py-2 font-bold"
					href="https://coloop.ai"
					target="_blank"
				>
					Learn More
				</a>
			</div>
		</div>

		<div class="box flex h-[47%] w-full flex-col p-8 max-xl:mt-4 max-xl:h-full">
			<div class="flex h-full flex-col">
				<div class="flex-row-items-center flex">
					<img class="mt-[5px] h-8 w-8 rounded-md" src="/projects/exp-logo.webp" alt="exp" />
					<h1 class="ml-3 text-[28px] font-semibold max-sm:text-2xl">EXP Bots</h1>
				</div>
				<div class="mt-4 flex flex-col">
					<p class="text-sm text-[#DADDE7]">
						EXP is a video game clan with a community discord server with over <strong
							>15,000 members</strong
						> with a custom suite of bots providing a bank system, giveaways, moderation and more.
					</p>
					<div class="mt-4 flex flex-col">
						<h2 class="text-xl font-medium">Stack</h2>
						<div class="mt-2 flex flex-row flex-wrap">
							<div class="project-technology-container">
								<img
									class="project-technology-icon"
									src="/skills/typescript.svg"
									alt="typescript"
								/>
								<p class="project-technology-text">Typescript</p>
							</div>
							<div class="project-technology-container">
								<img class="project-technology-icon" src="/skills/bun.svg" alt="bun" />
								<p class="project-technology-text">Bun</p>
							</div>
							<div class="project-technology-container">
								<img class="project-technology-icon" src="/skills/turso.svg" alt="turso" />
								<p class="project-technology-text">TursoDB</p>
							</div>
						</div>
					</div>
				</div>
			</div>
			<div class="flex w-full flex-row justify-end">
				<a
					class="w-fit rounded-md border border-white border-opacity-5 bg-[#111111] px-4 py-2 font-bold"
					href="/projects/exp"
				>
					Learn More
				</a>
			</div>
		</div>

		<!-- <div class="box flex h-[30%] w-full flex-col p-8 max-xl:mt-4 max-xl:h-full">
			<div class="flex h-full flex-col">
				<div class="flex-row-items-center flex">
					<img
						class="mt-[4px] h-8 w-8"
						src="/projects/obsidian-notes-ai-logo.svg"
						alt="obsidian-notes-ai"
					/>
					<h1 class="ml-3 text-[28px] font-semibold max-sm:text-2xl">Notes AI</h1>
				</div>
				<div class="mt-4 flex flex-col">
					<p class="text-sm text-[#DADDE7]">
						I built this project to learn how to use generative AI APIs, and practice my Next.js and
						tRPC skills.
					</p>
					<p class="mt-2 text-sm text-[#DADDE7]">
						Upload markdown files (mine come from obsidian), and ask the LLM questions about your
						notes.
					</p>
					<div class="mt-4 flex flex-col">
						<h2 class="text-xl font-medium">Stack</h2>
						<div class="mt-2 flex flex-row flex-wrap">
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
						</div>
					</div>
				</div>
			</div>
			<div class="flex w-full flex-row items-center justify-end">
				<a href="https://github.com/thereal-atom/obsidian-notes-ai" target="_blank">
					<img class="h-8 w-8" src="/socials/github.svg" alt="github" />
				</a>
				<a
					class="ml-4 w-fit rounded-md border border-white border-opacity-5 bg-[#111111] px-4 py-2 font-bold"
					href="/projects/obsidian-notes-ai"
				>
					Learn More
				</a>
			</div>
		</div> -->
		<!-- <div class="box flex flex-col w-full h-[47%] p-8 max-xl:h-full max-xl:mt-4">
            <div class="flex flex-col h-full">
                <h1 class="text-3xl font-semibold max-sm:text-2xl">From Scratch</h1>
                <div class="flex flex-col mt-4">
                    <p class="text-sm text-[#DADDE7]">A series of projects I created to learn fundamentals across software engineering as well as solidify my typescript and rust programming skills.</p>
                    <p class="text-sm text-[#DADDE7] mt-2">Projects include a blockchain, a neural network, physics simulation, encryption and more implementations from scratch.</p>
                    <div class="flex flex-col mt-4">
                        <h2 class="text-xl font-medium">Stack</h2>
                        <div class="flex flex-row flex-wrap mt-2">
                            <div class="project-technology-container">
                                <img
                                    class="project-technology-icon"
                                    src="/skills/typescript.svg"
                                    alt="typescript"
                                />
                                <p class="project-technology-text">Typescript</p>
                            </div>
                            <div class="project-technology-container">
                                <img
                                    class="project-technology-icon"
                                    src="/skills/rust.svg"
                                    alt="rust"
                                />
                                <p class="project-technology-text">Rust</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-row justify-end w-full">
                <a
                    class="w-fit px-4 py-2 font-bold bg-[#111111] border border-white border-opacity-5 rounded-md"
                    href="/projects/from-scratch"
                >
                    Learn More
                </a>
            </div>
        </div> -->
	</div>
</div>

<style lang="postcss">
	.box {
		@apply rounded-[32px] border border-white border-opacity-5 bg-[#161616];
	}

	.box-custom-bg {
		@apply rounded-[32px] border border-white border-opacity-5 max-md:rounded-[16px];
	}

	.skill-container {
		@apply mb-2 mr-2 flex h-fit flex-row items-center rounded-[8px] border border-white border-opacity-5 bg-[#242424] p-4 py-3 max-lg:p-3 max-md:p-2 max-xs:mb-1 max-xs:mr-1;
	}

	.skill-icon {
		@apply h-8 w-8 max-lg:h-6 max-lg:w-6 max-xs:h-4 max-xs:w-4;
	}

	.skill-text {
		@apply ml-2 font-medium max-md:ml-1 max-md:text-xs max-xs:text-[10px];
	}

	.project-technology-container {
		@apply mb-2 mr-2 flex h-fit flex-row items-center rounded-[4px] border border-white border-opacity-5 bg-[#242424] p-2;
	}

	.project-technology-icon {
		@apply h-4 w-4;
	}

	.project-technology-text {
		@apply ml-2 text-xs font-medium;
	}
</style>
