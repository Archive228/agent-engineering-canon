<div align="center">

<img src="assets/logo.svg" width="104" alt="agent-engineering canon logo">

# The Agent-Engineering Canon

**The talks that actually teach you to build agents — the ones the people who build them keep pointing to — collected in one place.**

18 videos · 0 courses · 0 fluff · sources are talks only

![videos 18](https://img.shields.io/badge/videos-18-3fb950) &nbsp;![all free](https://img.shields.io/badge/all-free%20on%20YouTube-79c0ff) &nbsp;![sources: talks only](https://img.shields.io/badge/sources-talks%20only-e3b341) &nbsp;![no paywall](https://img.shields.io/badge/paywall-none-3fb950)

</div>

---

Every link below is a **public talk or recorded video** by a named engineer or researcher. This repo does one thing: **collect and annotate them** so you don't have to rebuild the reading list yourself. Watch top-to-bottom and you go from "what is an agent" to "why my hours-long agent drifts and how to stop it."

**On sources:** the only sources here are the videos themselves — each is credited with speaker, channel, and link. Nothing is reproduced, and no other repositories or products are listed. If a talk changed how someone builds, it's here; if it's marketing, it isn't.

---

## I. Foundations — how to even think about this

- **Software Is Changing (Again)** — Andrej Karpathy *(Y Combinator · ~40m)* → the "Software 3.0 / decade of agents" framing; why the scaffolding around the model is the job now.
  https://www.youtube.com/watch?v=LCEmiRjPEtQ
- **What You MUST Know About AI Engineering** — Chip Huyen *(The MAD Podcast)* → a systems view of the whole AI-engineering stack from the author of *AI Engineering*.
  https://www.youtube.com/watch?v=p7F4f42iZ-c

## II. Effective agents — the principles

- **How We Build Effective Agents** — Barry Zhang, Anthropic *(AI Engineer · ~15m)* → don't over-apply agents, keep them simple, think from the agent's point of view.
  https://www.youtube.com/watch?v=D7_ipDqhtwk
- **12-Factor Agents: Patterns of Reliable LLM Applications** — Dexter Horthy, HumanLayer *(AI Engineer · ~17m)* → the manifesto for agents that don't fall over in production.
  https://www.youtube.com/watch?v=8kMaTybvDUw
- **Don't Build Agents, Build Skills Instead** — Barry Zhang & Mahesh Murag, Anthropic *(AI Engineer · ~16m)* → composable folders of procedural knowledge, loaded on demand, beat bespoke agents.
  https://www.youtube.com/watch?v=CEvIs9y1uog

## III. The harness — keeping agents on-task for hours

- **Build Agents That Run for Hours (Without Losing the Plot)** — Ash Prabaker & Andrew Wilson, Anthropic *(AI Engineer · ~1h15m)* → context rot, generator–evaluator loops, clean multi-session handoff. The most on-theme talk in the list.
  https://www.youtube.com/watch?v=mR-WAvEPRwE
- **Context Engineering Our Way to Long-Horizon Agents** — Harrison Chase, LangChain *(Sequoia)* → why long-horizon agents need a harness and feedback loops, not just a bigger model.
  https://www.youtube.com/watch?v=vtugjs2chdA
- **Advanced Context Engineering for Agents** — Dexter Horthy *(Context Engineering SF / Chroma)* → subagent design and compaction for shipping large features without the agent going off the rails.
  https://www.youtube.com/watch?v=VvkhYWFWaKI

## IV. Context engineering — less context, not more

- **Context Engineering for Agents** — Lance Martin, LangChain *(Latent Space · ~1h)* → the four moves — write, select, compress, isolate — for context that floods in from tool calls.
  https://www.youtube.com/watch?v=_IlTcWciEC4
- **Context Engineering for AI Agents (with Manus)** — Yichao "Peak" Ji (Manus) & Lance Martin *(LangChain · ~1h)* → battle-tested production lessons: KV-cache stability, masking tools instead of removing them, filesystem-as-context.
  https://www.youtube.com/watch?v=6_BcCthVvb8

## V. Memory — beyond the context window

- **Stateful Agents** — Charles Packer, Letta / MemGPT *(AI Engineer · ~1h20m)* → LLM-as-OS: core vs archival memory, and managing long-term memory the model can't hold.
  https://www.youtube.com/watch?v=E0k9Ppq6yXY
- **Stop Using RAG as Memory** — Zep AI → why retrieval isn't memory, and what an actual memory layer looks like.
  https://www.youtube.com/watch?v=ZNqGFsTyhvg

## VI. Coding agents — how the builders build

- **Claude Code & the Evolution of Agentic Coding** — Boris Cherny, Anthropic *(AI Engineer · ~18m)* → from the person who built Claude Code, how the tool and the workflow actually evolved.
  https://www.youtube.com/watch?v=Lue8K2jqfKk
- **Engineering Practices That Make Coding Agents Work** — Simon Willison *(The Pragmatic Engineer · ~28m)* → concrete day-to-day habits that separate "the agent helps" from "the agent ships."
  https://www.youtube.com/watch?v=owmJyKVu5f8

## VII. Evals & reasoning — the skills nobody teaches

- **Why AI Evals Are the Hottest New Skill for Product Builders** — Hamel Husain & Shreya Shankar *(Lenny's Podcast)* → if you can't measure it, you can't ship it; evals as the real bottleneck.
  https://www.youtube.com/watch?v=BsWxPI9UM4c
- **AI Progress Is About to Rapidly Accelerate** — Sholto Douglas & Trenton Bricken, Anthropic *(Dwarkesh Podcast · ~9m clip)* → why RL on LLMs finally works and how models actually reason inside.
  https://www.youtube.com/watch?v=UeI29-AdhQI

## Go deeper — foundations from scratch

- **Stanford CS336: Language Modeling from Scratch** — Tatsunori Hashimoto & Percy Liang *(Stanford Online)* → build an LLM end-to-end; the most rigorous public course on what's inside the models you build on.
  https://www.youtube.com/watch?v=SQ3fZ1sAqXI
- **Stanford CS25 V5: Large Language Model Reasoning** — Denny Zhou, Google DeepMind *(Stanford Online · ~1h)* → chain-of-thought, self-consistency, and the limits of SFT, from the researcher behind them.
  https://www.youtube.com/watch?v=ebnX5Ur1hBk

---

## How to use it

Watch **I → II → III** first — that's the spine (think, then principles, then the harness). Then pull IV–VII as you hit the wall each one describes. The whole canon is a few evenings; it replaces a shelf of paid "AI agent" courses.

## What this is (and isn't)

- **Is:** a curated, annotated index of public talks. Every entry links to its source and credits the speaker and channel.
- **Isn't:** a course, a paywall, or a list of tools/repos to install. The only things collected here are the videos.
- Titles and speakers were verified against the live videos at the time of writing. All credit belongs to the speakers and channels linked above.

<div align="center">

Collected & annotated by **@ArchiveExplorer**. If it saved you the hunt, ⭐ it.

</div>
