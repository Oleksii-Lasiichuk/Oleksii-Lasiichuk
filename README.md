# Oleksii Lasiichuk

CS student at [Ukrainian Catholic University](https://ucu.edu.ua/en/). Co-founder and CEO of [BFS](https://beyond-first-sight.com), automated image annotation for teams.

I build LLM systems and the boring parts around them, which turn out to be most of the work.

[LinkedIn](https://www.linkedin.com/in/oleksii-lasiichuk-9a90b934a/) · [Email](mailto:lasiichukol@gmail.com)

## Projects

**[Daily Coach](https://github.com/Oleksii-Lasiichuk/daily-coach)** · [live](https://coach.lasiichuk.com)
<br>You tell it how you slept and what you ate, in Ukrainian or English. It reads HRV and training load from intervals.icu, decides what kind of day it is, and sends an adjusted workout to a Garmin watch once you tap the button. Each of its nine LLM components is evaluated on its own against a simple baseline. Calorie estimates, for example, are off by 72 kcal on average on NutriBench, against 191 for guessing the mean. My brother and I use it every day.

**[MedAI](https://github.com/ArseniiStratiuk/Medical-AI)** · Jury Choice, SoftServe Agent Force Hackathon
<br>Team project. I built the Claude orchestrator, which runs five specialist medical models (MedGemma, MedSigLIP, HeAR) in parallel and sends their outputs through a judge agent. I also did the GPU inference on Modal, the Cloud Run deploy, and the FastAPI + Next.js layer. Reports include GradCAM heatmaps, so a doctor can see what the model was looking at.

**[News Aggregator](https://github.com/Oleksii-Lasiichuk/news-aggregator)**
<br>Every two hours an n8n workflow pulls 11 news sources. Llama 3.3 70B on Groq summarizes them and ranks them against my interests, the results go into Supabase, and a static site on GitHub Pages is rebuilt. It runs on a free-tier GCP VM and has cost $0 so far.
