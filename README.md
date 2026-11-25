<h1 align="center">Asad Ansari</h1>

<p align="center">
  <b>New grad AI/ML engineer</b> · LLM apps and agents · On-device AI · Computer vision<br/>
  BCS Honours, AI & Machine Learning stream @ Carleton University (2026) · Ottawa, Canada
</p>

<p align="center">
  <a href="https://asad-ansari.dev/"><img src="https://img.shields.io/badge/Portfolio-111111?style=flat&logo=vercel&logoColor=white" alt="Portfolio"/></a>
  <a href="https://www.linkedin.com/in/asad-ansari-ontario"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:asad.n.ansari.03@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email"/></a>
  <img src="https://img.shields.io/badge/Open%20to-New%20grad%20AI%20%2F%20ML%20roles%20in%20Canada-2ea44f?style=flat" alt="Open to new grad AI/ML roles in Canada"/>
</p>

---

### About me

- **Shipped [Plateful](https://apps.apple.com/ca/app/plateful-calorie-tracker/id6804057580)**, an iPhone calorie tracker on the App Store that estimates meals on-device with Apple's Foundation Models
- **Built an operations platform and AI support agent** for a vending company, in daily use across 200+ machines and 5 drivers (volunteer project)
- **Interned at Enbridge** (AI & Data Solutions), testing vision-language models on Azure and building an Azure Functions API over Databricks
- **Interned at Brookfield Renewable** (Data & Systems), building executive Power BI dashboards on 3M+ records
- **Teaching assistant for three Carleton CS courses**, including Introduction to Reinforcement Learning
- I like finding out what new models can actually do, then turning that into something people use
- Looking for **new grad AI engineering, ML engineering and data roles** across Canada, open to relocating

---

### Featured projects

| Project | What it does | Highlights | Stack |
|---|---|---|---|
| **Plateful**<br/>[App Store](https://apps.apple.com/ca/app/plateful-calorie-tracker/id6804057580) · [Website](https://platefulhq.com) | Calorie and macro tracker for iPhone. Log meals by voice, photo, barcode or text, with your data kept on the phone | **Live on the App Store.** Four-tier estimation: on-device Apple model → local USDA FoodData Central database → Apple Private Cloud Compute → Gemini fallback | Swift, Apple Foundation Models, SQLite, Gemini API |
| **Vending operations platform + AI agent**<br/>*(private)* | Runs day-to-day operations for a vending company: machines, refills, drivers and admins, plus an AI agent for support | **In live use across 200+ machines and 5 drivers** | Next.js, TypeScript, Prisma, PostgreSQL (Supabase), NextAuth |
| **PulmoLens**<br/>[Repo](https://github.com/anaCS-26/Pulmolens-model) · [Live demo](https://victorious-sky-0836ce10f.3.azurestaticapps.net) | Reads chest X-rays for 14 conditions, shows where the model is looking, and writes a summary backed by clinical guidelines | **Mean AUC 0.85** across 14 pathologies (NIH ChestX-ray14). Grad-CAM++ heatmaps, RAG over BTS, NICE and Fleischner guidelines, LLM eval harness with a cross-family judge | PyTorch (DenseNet121 + CBAM), LangChain, Pinecone, Gemma, Azure |
| **Surgical tool tracking**<br/>[Repo](https://github.com/anaCS-26/Multi-tool-detection-with-YOLO) | Detects and tracks 7 kinds of surgical instruments in laparoscopic surgery video | YOLOv11 fine-tuned on Cholec80, DeepSORT tracking and trajectory smoothing. Two-person course project | Python, Ultralytics YOLO, OpenCV, DeepSORT |
| **AsadGPT**<br/>[Try it](https://asad-ansari.dev/) · [Repo](https://github.com/anaCS-26/Personal-Website) | Chat assistant on my portfolio that answers questions about my work, with links into the site | Grounded in one knowledge file loaded into the prompt, so no vector database to maintain | Next.js, TypeScript, Tailwind, Claude API |
| **Hop On SMP**<br/>[Dashboard](https://hoponsmp.vercel.app) · [Repo](https://github.com/anaCS-26/hopon-smp) | Self-hosted Minecraft server on Oracle Cloud's free tier, with a web dashboard to run it without SSH | **Live, with friends playing.** Local backups every 6 hours, encrypted off-site backups daily, plus alerts | JavaScript, Oracle Cloud, Linux, Vercel |

**Also built:** [grb-fsr](https://github.com/anaCS-26/grb-fsr), an AMD FSR 4 upscaling mod for Ghost Recon Breakpoint published on [Nexus Mods](https://www.nexusmods.com/ghostreconbreakpoint/mods/2243) · [claude-themes](https://github.com/anaCS-26/claude-themes), backdrop themes for the Claude Code desktop app

---

### Tech stack

- **Languages:** Python, TypeScript, Swift, SQL, Java
- **AI / ML:** PyTorch, Anthropic, OpenAI and Gemini APIs, Apple Foundation Models, LangChain, Ultralytics YOLO, OpenCV
- **Backend & data:** FastAPI, Next.js, Prisma, PostgreSQL, Supabase, Databricks, Power BI
- **Cloud & tools:** Azure (Functions, AI Foundry), AWS, Oracle Cloud, Vercel, Git, Claude Code
