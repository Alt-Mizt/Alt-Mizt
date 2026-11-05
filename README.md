# Thato Tladi

Wrangling agents, making friends along the way, and trying to change the world, or at least my own communities.

### The Model Index

[themodelindex.org](https://themodelindex.org)

Every major AI model since ChatGPT, measured from third-party evidence: 376 models tracked and 257 scored across 22 labs, closed and open side by side, with what they cost. I built it and run it myself. A pipeline checks the sources every 30 minutes and the site updates itself.

Then it asks what all of that means for people, country by country. The World view covers 215 countries and territories: who can reach these models, what a $20 plan costs against what households there live on, who is online, who is using them and where they get built. That plan is 0.57% of the median living standard in Switzerland and 99% in Zambia. For about 4.6 billion people it is more than a tenth.

### Speech recognition for all 11 South African languages

I fine-tuned a 3-billion-parameter open speech model on all 11 official languages for under $15 of GPU. On read speech it cut errors by more than half and already beats Whisper large-v3 on South African English. At the other end I'm training a 65-million-parameter one, 73 MB, to do the same job on a phone with no internet. Leaderboard coming soon.

### forge

[forge-core](https://github.com/Alt-Mizt/forge-core)

Plug in your GPU accounts, run your training script, and forge keeps it going. It starts the job wherever you have free GPU time: a Kaggle account, a Modal account, your own machine. When a session ends it saves a snapshot and carries on somewhere else from the exact step it stopped at. I ran a job that started on Modal and finished on Kaggle, and its final weights matched an uninterrupted run bit for bit. It's for students, researchers and anyone whose compute comes in pieces.

### Agents and inference

I'm really into agents, an aspiring agentic cowboy if you like. I love handing a fleet of them a problem that's too big for one person and seeing how far we get. I build whole pipelines out of them too, for media, for code and for whatever else the job needs. I enjoy dabbling with different kinds of hardware to try these pipelines on, ranging from RTX 5090s to the PRO 6000 to DGX Sparks (wherever I can rent for the best deals!). My other rabbit hole, connected to all of this, is inference, making the models and those pipelines run much faster and cheaper. The last thing I built starts answering in under three seconds for under two cents.

Most repos are private today. I've got a lot of cool open source projects I've been working on in the back, and I'll start pushing them up here soon. forge is the first. My first fix merged upstream is in gVisor, the sandbox Google runs Cloud Run on: [google/gvisor#15445](https://github.com/google/gvisor/pull/15445).

I write about AI and what it means for Africa on [LinkedIn](https://www.linkedin.com/in/thato-tladi-9001b827a/).
