<script>
    import constants from "$lib/constants";
</script>

<div class="relative flex items-center justify-center w-screen h-full min-h-screen bg-[#101010] text-white">
    <div
        class="absolute w-screen h-full z-10 pointer-events-none"
        style="background-size: 64px; background-repeat: repeat; background-image: url('/fuzzy.png'); opacity: 0.06;"
    ></div>
    <div class="flex flex-row items-center justify-between w-full h-[900px] z-[100] p-8 max-xl:flex-col max-xl:h-full max-sm:p-4">
        <div class="flex flex-col justify-between w-[74.5%] h-full max-xl:w-full">
            <div class="flex flex-row justify-between w-full h-[32%] max-xl:h-[250px] max-md:h-auto">
                <div class="box w-auto h-full aspect-square relative max-md:hidden">
                    <img
                        class="w-full h-full object-cover rounded-[32px] opacity-80 hover:opacity-100 transition-opacity"
                        src="/oscar.jpg"
                        alt="oscar"
                    />
                </div>
                <div class="box w-full h-full flex flex-col mx-4 p-8 max-xl:mr-0 max-md:mx-0 max-sm:p-6">
                    <h1 class="text-3xl font-semibold max-sm:text-2xl">Oscar Falemara</h1>
                    <span class="w-fit px-2 py-1 bg-[#111111] text-[8px] font-medium border border-white border-opacity-5 rounded-md">🚀 Open to Opportunities</span>
                    <p class="mt-8 text-[#DADDE7] max-2xl:mt-4 max-sm:text-sm">I'm a self-taught <span class="font-medium underline">full stack web developer</span> from <span class="pl-1 pr-1.5 py-0.5 bg-[#111111] font-medium border border-white border-opacity-5 rounded-md">📍London</span> with over 4 years of experience.</p>
                    <p class="mt-4 text-[#DADDE7] max-sm:text-sm">Software engineer, aerospace engineering student, entrepreneur and freelancer.</p>
                </div>
                <div class="box w-auto h-full aspect-square max-xl:hidden"></div>
            </div>
            <div class="flex flex-col justify-between h-[66.5%] max-xl:flex max-xl:flex-col-reverse">
                <div class="flex flex-row justify-between h-[49%] max-xl:h-[200px] max-xl:mt-4 max-md:mt-0 max-md:flex-col max-md:h-full">
                    <div class="box w-[49.5%] h-full relative overflow-hidden max-md:w-full max-md:h-[250px] max-sm:h-[200px] max-md:mt-4">
                        <img
                            class="absolute -top-8 opacity-60 hover:opacity-100 hover:scale-105 transition-all max-2xl:static max-2xl:w-auto max-2xl:h-full max-2xl:min-w-full max-2xl:min-h-full max-2xl:object-cover"
                            src="/cribgoch.jpg"
                            alt="cribgoch"
                        />
                        <p class="absolute right-6 top-6 pr-3 pl-2.5 py-2 bg-[#1B1B1B] text-xs border border-white border-opacity-5 rounded-md">🏔️ I also like climbing mountains</p>
                        <p class="absolute left-8 bottom-4 text-[8px]">Crib Goch, Wales</p>
                    </div>
                    <div class="box w-[49.5%] h-full relative overflow-hidden max-md:w-full max-md:h-[250px] max-sm:h-[200px] max-md:mt-4">
                        <img
                            class="absolute -top-4 opacity-60 hover:opacity-100 hover:scale-105 transition-all max-2xl:static max-2xl:w-auto max-2xl:h-full max-2xl:min-w-full max-2xl:min-h-full max-2xl:object-cover"
                            src="/corfu.jpg"
                            alt="corfu"
                        />
                        <p class="absolute right-6 top-6 pr-3 pl-2.5 py-2 bg-[#1B1B1B] text-xs border border-white border-opacity-5 rounded-md">📷 And I like photography</p>
                        <p class="absolute left-8 bottom-4 text-[8px]">Corfu, Greece</p>
                    </div>
                </div>
                <div class="flex flex-row justify-between h-[49%] max-xl:flex-row-reverse max-xl:h-[250px] max-xl:mt-4 max-md:h-[150px]">
                    <div class="grid grid-cols-2 gap-2 w-auto h-full aspect-square max-xl:ml-4">
                        <a
                            class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-black transition-all"
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
                            class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-[#24292e] transition-all"
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
                            class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-[#0a66c2] transition-all"
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
                            class="box-custom-bg bg-[#151515] w-auto h-full aspect-square p-9 max-md:p-5 hover:bg-[#c71610] transition-all"
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
                    <div class="box w-full h-full flex flex-col ml-4 p-8 overflow-hidden max-xl:ml-0">
                        <h1 class="text-3xl font-semibold mt-1">Skills</h1>
                        <div class="flex flex-row mt-8 w-full overflow-hidden max-xl:grid-cols-4 max-xl:mt-4">
                            <div class="w-24 h-24 min-w-[96px] p-6 bg-[#101010] rounded-[16px] max-xl:w-16 max-xl:h-16 max-xl:min-w-[64px] max-xl:p-4">
                                <img
                                    src="/skills/typescript.svg"
                                    alt="typescript"
                                />
                            </div>
                            <div class="w-24 h-24 min-w-[96px] p-6 ml-2 bg-[#101010] rounded-[16px] max-xl:w-16 max-xl:h-16 max-xl:min-w-[64px] max-xl:p-4">
                                <img
                                    src="/skills/sveltekit.svg"
                                    alt="sveltekit"
                                />
                            </div>
                            <div class="w-24 h-24 min-w-[96px] p-6 ml-2 bg-[#101010] rounded-[16px] max-xl:w-16 max-xl:h-16 max-xl:min-w-[64px] max-xl:p-4">
                                <img
                                    src="/skills/nodejs.svg"
                                    alt="nodejs"
                                />
                            </div>
                            <div class="w-24 h-24 min-w-[96px] p-6 ml-2 bg-[#101010] rounded-[16px] max-xl:w-16 max-xl:h-16 max-xl:min-w-[64px] max-xl:p-4">
                                <img
                                    src="/skills/tailwindcss.svg"
                                    alt="tailwindcss"
                                />
                            </div>
                            <div class="w-24 h-24 min-w-[96px] p-6 ml-2 bg-[#101010] rounded-[16px] max-xl:w-16 max-xl:h-16 max-xl:min-w-[64px] max-xl:p-4">
                                <img
                                    src="/skills/rust.svg"
                                    alt="rust"
                                />
                            </div>
                            <div class="w-24 h-24 min-w-[96px] p-6 ml-2 bg-[#101010] rounded-[16px] max-xl:w-16 max-xl:h-16 max-xl:min-w-[64px] max-xl:p-4">
                                <img
                                    src="/skills/python.svg"
                                    alt="python"
                                />
                            </div>
                            <div class="w-24 h-24 min-w-[96px] p-6 ml-2 bg-[#101010] rounded-[16px] max-xl:w-16 max-xl:h-16 max-xl:min-w-[64px] max-xl:p-4">
                                <img
                                    src="/skills/html.svg"
                                    alt="html"
                                />
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="flex flex-col justify-between w-[24.5%] h-full max-xl:w-full max-xl:h-full max-xl:mt-4"> 
            <div class="box w-full h-[49%] max-xl:h-[300px]"></div>
            <div class="box w-full h-[49%] max-xl:h-[300px] max-xl:mt-4"></div>
        </div>
    </div>
</div>

<style lang="postcss">
    .box {
        @apply rounded-[32px] bg-[#151515] border border-white border-opacity-5;
    }

    .box-custom-bg {
        @apply rounded-[32px] border border-white border-opacity-5 max-md:rounded-[16px];
    }
</style>