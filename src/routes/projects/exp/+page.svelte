<div class="flex flex-col h-full min-h-screen w-full mt-16 px-64 max-2xl:px-48 max-xl:px-8 max-md:px-0">
    <h1 class="text-3xl font-bold max-md:text-2xl">EXP Discord Bots</h1>
    <div class="flex flex-col mt-8 p-8 bg-[#161616] border border-white border-opacity-5 rounded-[32px]">
        <p>EXP is a video game clan which has a community discord server with over <strong>11,000 current members</strong> with a suite of custom discord bots.</p> 
        <p>Across the bots, there are lots of features that the members can take advantage of:</p>
        <ul>
            <li>The main feature is the bank: members can donate their in-game gems to the clan, and receive balance within the discord server upon which they can gain interest, and gift gems to other members. The bank holds over <strong>10T gems</strong> for over <strong>5,000 members</strong>.</li>
            <li>Another feature is a robust giveaway system. There are 4 different types of giveaways that run multiple times a day, resulting in 1000s of dollars worth of in-game items given away per month. A new feature allows the users to host giveaways themselves with over 300B gems given away so far.</li>
            <li>There is a moderation system the admins can use in order to keep the peace within the discord server. This allows the moderation actions to be logged and viewed which makes for a better organized server.</li>
            <li>For each user feature, there are admin commands to allow the admins to manage everything.</li>
        </ul>
        <p>The bots are hosted on a VPS with a custom CI/CD solution which allows for rapid auto deployments and minimal down time.</p>
        <div class="flex flex-col mt-4">
            <h2 class="text-2xl font-semibold max-md:text-xl">Stack</h2>
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
    <h2 class="text-2xl font-semibold mt-8 max-md:text-xl">What I learned</h2>
    <div class="flex flex-col mt-8 p-8 bg-[#161616] border border-white border-opacity-5 rounded-[32px]">
        <div class="flex flex-col">
            <p>This project was the biggest production project I had worked on. As such, I had to take a lot into consideration when designing the architecture and the codebase.</p>
            <h3 class="text-lg font-medium my-4 max-md:text-base">A Production Codebase - Principles</h3>
            <p>Generally speaking, I practiced lots of production codebase concepts (consistent and detailed variable names, keep it stupid simple, separation of concerns, etc etc), and learned to think ahead with the code, ensuring it's easy to read, test, extract, etc, as it might need to be improved and updated in the future.</p>
            <p>For example, I had originally use json files as local storage, but the code to handle that was embedded within one specific feature, which turned out to be a mistake, as I ended up extracting that logic into a custom class/functions. After that, I took extra care to think about whether to write global functions (making them easy to use in the future, but taking extra time to code), or to keep them within features (saving coding time, but increasing it if the functionality needs to be extracted in future features). </p>
            <p class="underline">To put it simply, it taught me to consider the implications of coding something one way, rather than coding the first thing that comes to mind that works.</p>
            <h3 class="text-lg font-medium my-4 max-md:text-base">The Bank - Database</h3>
            <p>The original focus of these bots was the bank system. Users can donate gems to the clan, and the bot would keep track of their balance and would issue interest on an hourly basis.</p>
            <p>It was important that this system worked well, as big issues end up costing the admins a lot of money, and could leave users unhappy.</p>
            <p>One issue I came across was that when users would gift, the recipient might not receive the gift (but the sender was debited), or vice versa. <span class="underline">I learned about database atomicty, and used database transactions for any features where balance was transferred.</span></p>
            <h3 class="text-lg font-medium my-4 max-md:text-base">Giveaways - Performance</h3>
            <p>The bots have two types of giveaways - clan and user giveaways. Clan giveaways would run a few times a day, and users would get the prizes from the clan admins. User giveaways were run by users, where other users could enter to win gems.</p>
            <p>With clan giveaways, there were thousands of users who each had hundreds of entries, resulting in a massive array of user entries that would have to be shuffled, and then a user id would be selected. This original implementation was really slow and only worked fine for a few hundred users, but once there were multiple thousands of users, it could take up to 40 minutes to draw a winner.. I switched to storing the entries with a javascript map, with each user simply being a "entry" in the map, and a random number to select the winner which drastically reduced the time it took to draw.</p>
        </div>
    </div>
</div>

<style lang="postcss">
    p, li {
        @apply my-1 text-[#DADDE7] max-md:text-xs;
    }

    ul {
        @apply list-disc ml-4 my-4;
    }

    .project-technology-container {
        @apply flex flex-row items-center h-fit mt-4 p-2 bg-[#242424] border border-white border-opacity-5 rounded-[4px] mr-2 mb-2 max-md:py-1.5;
    }

    .project-technology-icon {
        @apply w-6 h-6 max-md:w-4 max-md:h-4;
    }

    .project-technology-text {
        @apply text-sm ml-2 font-bold max-md:text-xs;
    }
</style>