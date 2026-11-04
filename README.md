<p align="center">
  <img src="assets/profile/hero.svg" alt="LatentSpace7 — Full-stack AI engineer. Curious by default." width="100%" />
</p>

<p align="center">
  <a href="#projects">Projects</a> &nbsp; / &nbsp;
  <a href="#the-human-behind-the-terminal">The human</a> &nbsp; / &nbsp;
  <a href="https://huggingface.co/latentspace7">🤗 Hugging Face</a> &nbsp; / &nbsp;
  <a href="https://www.linkedin.com/in/dolwinf/">Let's connect ↗</a>
</p>

## The human behind the terminal

Hey, I'm **LatentSpace7** 👋 A full-stack AI engineer with years of experience building **AI applications, RAG pipelines, and agentic systems**, from the interface to the infrastructure.

I'm currently working as an **independent contractor** under my brand [**Vector Space**](https://vectorspace.com.au), migrating a large legacy codebase to a modern stack and building agentic systems around real business workflows.

I've just completed my **Master's in Artificial Intelligence at La Trobe University**. I've embraced **AI-native development** and I'm a big fan: AI as a collaborator throughout the build, with human judgement and evaluation keeping us honest.

Find me on [<img src="assets/profile/linkedin.svg" alt="" width="16" height="16" /> LinkedIn ↗](https://www.linkedin.com/in/dolwinf/), or [visit vectorspace.com.au to chat or talk with Spacy ↗](https://vectorspace.com.au/#contact)

> Powered by curiosity. Debugged by reality.

## Projects

<a href="https://github.com/latentspace7/EdgeDispatch">
  <img src="assets/profile/edgedispatch.svg" alt="01 — EdgeDispatch. Thesis for my Master's in AI at La Trobe University." width="100%" />
</a>

### [EdgeDispatch](https://github.com/latentspace7/EdgeDispatch) · Thesis for my Master's in AI at La Trobe University

**When should a local model handle the task, and when should it ask for backup?**

A local-first AI agent system built around **LFM2.5-2.6B**, a small language model fine-tuned with a LoRA adapter to make execution decisions based on reviewed task outcomes and assessed model capability. The adapter chooses `LOCAL` or `ESCALATE`, and the local base model or a remote model then handles the work. The thesis evaluates decision quality, answer quality, and remote execution API cost.

**Python · React · FastAPI · llama.cpp · LoRA · MCP**

[See a demo and explore the project ↗](https://github.com/latentspace7/EdgeDispatch#demo) &nbsp; · &nbsp; [Read the thesis ↗](https://github.com/latentspace7/EdgeDispatch/blob/main/docs/ltu_thesis_b_v1.pdf) &nbsp; · &nbsp; [Hugging Face 🤗](https://huggingface.co/latentspace7)

<br />

<a href="https://vectorspacetech.com/crowdflux/">
  <img src="assets/profile/02-crowdflux.svg" alt="02 — CrowdFlux. People in view. Insight on device." width="100%" />
</a>

### [CrowdFlux](https://vectorspacetech.com/crowdflux/) · On-device people counting for iPhone

**People in view. Insight on device.**

A native iOS app that turns a live camera view or imported video into people counts and local session reports. Uses **RF-DETR Nano through Core ML** for on-device person detection, **ByteTrack** for motion tracking, and **OSNet** appearance embeddings to reconnect people with anonymous session IDs. Review visible and peak counts, save optional annotated recordings, and export CSV reports.

**Swift · SwiftUI · Core ML · RF-DETR Nano · ByteTrack · OSNet**

[See a demo and explore the project ↗](https://github.com/latentspace7/crowdflux#demo) <sub>(private repository)</sub> &nbsp; · &nbsp; [Visit VectorSpace Apps ↗](https://vectorspacetech.com/) &nbsp; · &nbsp; [Explore CrowdFlux ↗](https://vectorspacetech.com/crowdflux/)

<p>
  <a href="https://apps.apple.com/th/app/crowdflux/id6821608555"><img src="assets/profile/download-on-the-app-store.svg" alt="Download CrowdFlux on the App Store" height="48" /></a>
</p>

<br />

<a href="https://github.com/latentspace7/LiveTranslate">
  <img src="assets/profile/03-livetranslate.svg" alt="03 — LiveTranslate. Live speech translation: a little less lost in translation." width="100%" />
</a>

### [LiveTranslate](https://github.com/latentspace7/LiveTranslate) · Speech → understanding

**For conversations that shouldn't need a language setting.**

A browser companion that turns nearby speech into live translated captions. Follow the original and translated text together, with optional spoken translations and a layout made for conversations on the go.

**React · TypeScript · FastAPI · WebSockets · Realtime audio**

[See a demo and explore the project ↗](https://github.com/latentspace7/LiveTranslate#demo) &nbsp; · &nbsp; [Open the app ↗](https://qwen-live-translate.vercel.app) <sub>(sign-in required)</sub>

<br />

<a href="https://github.com/latentspace7/spacebot">
  <img src="assets/profile/04-spacebot.svg" alt="04 — Spacebot. The bot behind Spacy: a little character, a proper conversation." width="100%" />
</a>

### [Spacebot](https://github.com/latentspace7/spacebot) · The bot behind Spacy

**A little character. A proper conversation.**

A reusable React chat widget with a caped, animated robot, streaming responses, optional live voice calls, light and dark themes, and lead capture. Built to bring personality to the interface while keeping the assistant's services replaceable: provider keys stay on your server, and the widget tells visitors when no backend is connected yet. **Spacy** is its Vector Space personality, with a natural Australian voice on calls.

**React · TypeScript · Motion · Streaming chat · WebRTC voice · Configurable integrations**

[See a demo and explore the project ↗](https://github.com/latentspace7/spacebot#demo) &nbsp; · &nbsp; [Visit Vector Space to chat or talk with Spacy ↗](https://vectorspace.com.au/#contact)

<br />

<a href="https://github.com/latentspace7/raid">
  <img src="assets/profile/05-raid.svg" alt="05 — RAID. Reddit AI Digest: less scrolling, more signal." width="100%" />
</a>

### [RAID](https://github.com/latentspace7/raid) · Reddit AI Digest

**Your subreddits, distilled. Your scrolling habit, mildly inconvenienced.**

Collects Reddit threads, summarises them with AI, and delivers a readable email digest with links to the original posts. Built around bounded async processing, with a CLI and an authenticated FastAPI endpoint.

**Python · FastAPI · Async I/O · LLM summarisation · Email**

[See a demo and explore the project ↗](https://github.com/latentspace7/raid#demo)

<br />

<a href="https://github.com/latentspace7/intelui">
  <img src="assets/profile/06-aerovista.svg" alt="06 — AeroVista Intelligence. Ask in plain English. Explore the answer." width="100%" />
</a>

### [AeroVista Intelligence](https://github.com/latentspace7/intelui) · Questions → interactive reports

**Ask in plain English. Explore the answer.**

Uses **CopilotKit's A2UI for intelligent UI** to turn natural-language questions into interactive airline reports. Inspect the generated SQL, explore charts and tables, and save reports to a dashboard with background refresh. Built on a synthetic PostgreSQL dataset with validated, read-only analytics queries.

**React · TypeScript · FastAPI · PostgreSQL · CopilotKit A2UI**

[See a demo and explore the project ↗](https://github.com/latentspace7/intelui#demo)

## Tools I reach for

<p>
  <img src="assets/profile/stack.svg" alt="Python, TypeScript, React, FastAPI, and Docker" width="700" />
</p>

Also in the mix: **RAG, Neo4j, Hugging Face, AWS, GCP, and a lot of evaluation.**

## Good problems welcome

Have an **AI engineering role**, a collaboration, or a problem worth building for? [Let's connect on LinkedIn ↗](https://www.linkedin.com/in/dolwinf/).

<p align="center">
  <img src="assets/profile/footer.svg" alt="Always learning. Usually building. Occasionally remembering to commit." width="100%" />
</p>
