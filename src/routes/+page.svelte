<script>
    import constants from "$lib/constants";
</script>

<div class="flex flex-row items-center justify-between w-full h-[900px] p-8 max-xl:flex-col max-xl:h-full max-sm:p-4">
    <div class="flex flex-col justify-between w-[74.5%] h-full max-xl:w-full">
        <div class="flex flex-row justify-between w-full h-[32%] max-xl:h-[250px] max-md:h-auto">
            <div class="box w-auto h-full aspect-square relative max-md:hidden">
                <img
                    class="w-full h-full object-cover rounded-[32px] opacity-80 hover:opacity-100 transition-opacity"
                    src="/oscar.webp"
                    alt="oscar"
                />
            </div>
            <div class="box w-full h-full flex flex-col mx-4 p-8 max-xl:mr-0 max-md:mx-0 max-sm:p-6">
                <h1 class="text-3xl font-semibold max-sm:text-2xl">Oscar Falemara</h1>
                <span class="w-fit mt-1 px-2 py-1 bg-[#242424] text-xs font-medium border border-white border-opacity-5 rounded-md">🚀 Open to Opportunities</span>
                <p class="mt-8 text-[#DADDE7] max-2xl:mt-4 max-sm:text-sm">I'm a self-taught <span class="font-medium underline">full stack web developer</span> from <span class="pl-1 pr-1.5 py-0.5 bg-[#242424] font-medium border border-white border-opacity-5 rounded-md text-nowrap">📍London</span> with over 4 years of experience.</p>
                <p class="mt-4 text-[#DADDE7] max-sm:text-sm">Substantial knowledge about systems programming, machine learning, blockchain and more.</p>
            </div>
            <div class="box w-auto h-full aspect-square max-xl:hidden">
                <img
                    class="w-auto h-full min-w-full min-h-full object-cover rounded-[32px] opacity-80 hover:opacity-100 transition-opacity"
                    src="/sunrise.webp"
                    alt="sunrise"
                />
            </div>
        </div>
        <div class="flex flex-col justify-between h-[66.5%] max-xl:flex max-xl:flex-col-reverse">
            <div class="flex flex-row justify-between h-[49%] max-xl:h-[200px] max-xl:mt-4 max-md:mt-0 max-md:flex-col max-md:h-full">
                <div class="box w-[49.5%] h-full relative overflow-hidden max-md:w-full max-md:h-[250px] max-md:mt-4 max-sm:h-[200px] max-xs:h-[160px]">
                    <img
                        class="absolute -top-8 opacity-60 hover:opacity-100 hover:scale-105 transition-all max-2xl:static max-2xl:w-auto max-2xl:h-full max-2xl:min-w-full max-2xl:min-h-full max-2xl:object-cover"
                        src="/cribgoch.webp"
                        alt="cribgoch"
                    />
                    <p class="absolute right-6 top-6 pr-3 pl-2.5 py-2 bg-[#242424] text-xs border border-white border-opacity-5 rounded-md">🏔️ I also like climbing mountains</p>
                    <p class="absolute left-8 bottom-4 text-[8px]">Crib Goch, Wales</p>
                </div>
                <div class="box w-[49.5%] h-full relative overflow-hidden max-md:w-full max-md:h-[250px] max-md:mt-4 max-sm:h-[200px] max-xs:h-[160px]">
                    <img
                        class="absolute -top-4 opacity-60 hover:opacity-100 hover:scale-105 transition-all max-2xl:static max-2xl:w-auto max-2xl:h-full max-2xl:min-w-full max-2xl:min-h-full max-2xl:object-cover"
                        src="/corfu.webp"
                        alt="corfu"
                    />
                    <p class="absolute right-6 top-6 pr-3 pl-2.5 py-2 bg-[#242424] text-xs border border-white border-opacity-5 rounded-md">📷 And I like photography</p>
                    <p class="absolute left-8 bottom-4 text-[8px]">Corfu, Greece</p>
                </div>
            </div>
            <div class="flex flex-row justify-between h-[49%] max-xl:flex-row-reverse max-xl:h-[270px] max-xl:mt-4 max-md:flex-col-reverse max-md:h-full max-md:w-full">
                <div class="grid grid-cols-2 gap-4 w-auto h-full aspect-square max-xl:ml-4 max-md:grid-cols-4 max-md:flex max-md:flex-row max-md:w-full max-md:h-auto max-md:aspect-auto max-md:ml-0 max-md:mt-4 max-xs:gap-2">
                    <a
                        class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-black transition-all max-md:w-full max-md:h-auto"
                        href={constants.socials.x.url}
                        target="_blank"
                    >
                        <img
                            class="w-full h-full"
                            src="/socials/x.svg"
                            alt="x"
                        />
                    </a>
                    <a
                        class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-[#24292e] transition-all max-md:w-full max-md:h-auto"
                        href={constants.socials.github.url}
                        target="_blank"
                    >
                        
                        <img
                            class="w-full h-full"
                            src="/socials/github.svg"
                            alt="github"
                        />
                    </a>
                    <a
                        class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-[#0a66c2] transition-all max-md:w-full max-md:h-auto"
                        href={constants.socials.linkedin.url}
                        target="_blank"
                    >
                        
                        <img
                            class="w-full h-full"
                            src="/socials/linkedin.svg"
                            alt="linkedin"
                        />
                    </a>
                    <a
                        class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-[#c71610] transition-all max-md:w-full max-md:h-auto"
                        href={constants.socials.email.url}
                        target="_blank"
                    >
                        
                        <img
                            class="w-full h-full"
                            src="/socials/email.svg"
                            alt="email"
                        />
                    </a>
                </div>
                <div class="box w-full h-full flex flex-col ml-4 p-8 overflow-hidden max-xl:ml-0 max-xl:py-6 max-md:py-4 max-md:px-6">
                    <h1 class="text-3xl font-semibold max-md:text-xl">Skills</h1>
                    <div class="flex flex-row flex-wrap mt-8 w-full overflow-hidden max-xl:grid-cols-4 max-xl:mt-4 max-md:mt-2">
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/typescript.svg"
                                alt="typescript"
                            />
                            <p class="skill-text">Typescript</p>
                        </div>
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/sveltekit.svg"
                                alt="sveltekit"
                            />
                            <p class="skill-text">SvelteKit</p>
                        </div>
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/nodejs.svg"
                                alt="nodejs"
                            />
                            <p class="skill-text">Node.js</p>
                        </div>
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/rust.svg"
                                alt="rust"
                            />
                            <p class="skill-text">Rust</p>
                        </div>
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/tailwindcss.svg"
                                alt="tailwindcss"
                            />
                            <p class="skill-text">Tailwind</p>
                        </div>
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/html.svg"
                                alt="html"
                            />
                            <p class="skill-text">HTML</p>
                        </div>
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/python.svg"
                                alt="python"
                            />
                            <p class="skill-text">Python</p>
                        </div>
                        <div class="max-md:hidden">
                            <div class="skill-container">
                                <img
                                    class="skill-icon"
                                    src="/skills/supabase.svg"
                                    alt="supabase"
                                />
                                <p class="skill-text">Supabase</p>
                            </div>
                        </div>
                        <div class="max-md:hidden">
                            <div class="skill-container">
                                <img
                                    class="skill-icon"
                                    src="/skills/react.svg"
                                    alt="react"
                                />
                                <p class="skill-text">React</p>
                            </div>
                        </div>
                        <div class="skill-container">
                            <img
                                class="skill-icon"
                                src="/skills/express.svg"
                                alt="express"
                            />
                            <p class="skill-text">express.js</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <div class="flex flex-col justify-between w-[24.5%] h-full max-xl:w-full max-xl:h-full max-xl:mt-4"> 
        <a
            class="text-3xl font-semibold max-sm:text-2xl"
            href="/projects"
        >
            Projects <span class="text-xs text-blue-400 font-medium">View All Projects</span>
        </a>
        <div class="box flex flex-col w-full h-[45%] p-8 max-xl:h-full max-xl:mt-4">
            <div class="flex flex-col h-full">
                <h1 class="text-3xl font-semibold max-sm:text-2xl">EXP Discord Bots</h1>
                <div class="flex flex-col mt-4">
                    <p class="text-sm text-[#DADDE7]">EXP is a video game clan with a community discord server with over <strong>11,000 members</strong> with a custom suite of bots providing a bank system, giveaways, moderation and more.</p>
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
                                    src="/skills/bun.svg"
                                    alt="bun"
                                />
                                <p class="project-technology-text">Bun</p>
                            </div>
                            <div class="project-technology-container">
                                <img
                                    class="project-technology-icon"
                                    src="/skills/turso.svg"
                                    alt="turso"
                                />
                                <p class="project-technology-text">TursoDB</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <div class="flex flex-row justify-end w-full">
                <a
                    class="w-fit px-4 py-2 font-bold bg-[#111111] border border-white border-opacity-5 rounded-md"
                    href="/projects/exp"
                >
                    Learn More
                </a>
            </div>
        </div>
        <div class="box flex flex-col w-full h-[47%] p-8 max-xl:h-full max-xl:mt-4">
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
        </div>
    </div>
</div>

<style lang="postcss">
    .box {
        @apply rounded-[32px] bg-[#161616] border border-white border-opacity-5;
    }

    .box-custom-bg {
        @apply rounded-[32px] border border-white border-opacity-5 max-md:rounded-[16px];
    }

    .skill-container {
        @apply flex flex-row items-center h-fit p-4 py-3 bg-[#242424] border border-white border-opacity-5 rounded-[8px] mr-2 mb-2 max-lg:p-3 max-md:p-2 max-xs:mr-1 max-xs:mb-1;
    }

    .skill-icon {
        @apply w-8 h-8 max-lg:w-6 max-lg:h-6 max-xs:w-4 max-xs:h-4;
    }

    .skill-text {
        @apply ml-2 font-medium max-md:ml-1 max-md:text-xs max-xs:text-[10px];
    }

    .project-technology-container {
        @apply flex flex-row items-center h-fit p-2 bg-[#242424] border border-white border-opacity-5 rounded-[4px] mr-2 mb-2;
    }

    .project-technology-icon {
        @apply w-4 h-4;
    }

    .project-technology-text {
        @apply text-xs ml-2 font-medium;
    }
</style>