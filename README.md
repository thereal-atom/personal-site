# oscar falemara

Welcome to my personal site:

I'm a self-taught full stack web developer from 📍London with over 4 years of experience.

Software engineer, aerospace engineering student, entrepreneur and freelancer.

- GitHub: https://github.com/thereal-atom
- Twitter: https://x.com/oscarfalll 
- LinkedIn: https://linkedin.com/in/oscarfalemara
- Email: falemaraoscar@gmail.com

## projects

### EXP Discord Bots

EXP is a video game clan which has a community discord server with over **15,000 members** with a suite of bots that I coded.

Across the bots, there are lots of features that the members can take advantage of:
- The main feature is the bank: members can donate their in-game gems to the clan, and receive balance within the discord server upon which they can gain interest, and gift gems to other members. The bank holds trillions of gems.
- Another feature is a robust giveaway system. There are 4 different types of giveaways that run multiple times a day, resulting in 1000s of dollars worth of in-game items given away per month. A new feature allows the users to host giveaways themselves with over **300B gems** given away so far.
- There is a moderation system the admins can use in order to keep the peace within the discord server. This allows the moderation actions to be logged and viewed which makes for a better organized server.
- For each user feature, there are admin commands to allow the admins to manage everything.

The bots are hosted on a VPS with a **custom CI/CD solution** which allows for rapid auto deployments and minimal down time.

They're coded with Typescript on the bun runtime, and the server uses elysia, and a turso database.

### Notes AI

I build this project to learn how to use generative AI APIs, and practice my Next.js and tRPC skills.

It's built with Next.js, tRPC and Tailwind via the create t3 template which was a very smooth experience. I am using the Google Gemini SDK and the Gemini 2.0 flash as well as text embedding models.

You can upload your markdown files (mine come from obsidian), and ask the LLM questions about your notes.

It'll reference your notes if it used them for it's response. Conversations are saved and chat history is applied to prompts.

[<img src="https://github.com/thereal-atom/personal-site/blob/main/static/examples/obsidian-notes-ai.png">](https://oscarfal.vercel.app)