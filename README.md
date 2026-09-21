# Interesting Repos

A running list of GitHub projects I've stumbled across and found genuinely interesting, each with a quick note on why.

## The List

- **[incoai/splash](https://github.com/incoai/splash)** — A local inference engine built specifically for Apple silicon Macs that serves small language models to coding agents and API clients. Uses specialized kernels, draft models, and per-model memory management to get fast, competitive inference running entirely on-device.

- **[V380-Ori/Astris.Binaries](https://github.com/V380-Ori/Astris.Binaries)** — Prebuilt binaries for Astris, a Nintendo Switch emulator for Apple silicon Macs on macOS 15+. It picks up where Ryujinx left off and retargets it at modern Mac hardware, which is a nice example of the emulation community keeping a project alive by porting it somewhere new.

- **[RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec)** — A Rust vector search index implementing Google's TurboQuant algorithm, with Python bindings for RAG systems. The compression is the headline: 10M documents in 4GB instead of 31GB, while still beating FAISS on search speed via hand-written SIMD kernels, and it indexes online with no training phase.

- **[amaancoderx/npxskillui](https://github.com/amaancoderx/npxskillui)** — A CLI that extracts a complete design system out of a website, repo, or local codebase and packages it as a skill Claude Code can use to build matching UIs. The clever part is that it's pure static analysis — no AI, no API keys, all local.

- **[ErTasselli/OpenTerminal](https://github.com/ErTasselli/OpenTerminal)** — A keyboard-driven, terminal-style trading dashboard that pulls market data from free public sources with no API keys or subscriptions. Fallback chains across providers keep it working when one source dies, and it covers options chains, crypto, economic calendars, and portfolio tracking locally.

- **[IceWhaleTech/ZimaOS](https://github.com/IceWhaleTech/ZimaOS)** — An open-source NAS operating system grown out of CasaOS, built with Buildroot for a small footprint and reliable over-the-air updates. Runs on Zima's own hardware but also on generic x86-64 boxes, making it an easy way to turn spare hardware into a real NAS.

- **[getumbrel/umbrel](https://github.com/getumbrel/umbrel)** — A home server OS for self-hosting, with 300+ apps in its own app store and support for anything from a Raspberry Pi 5 to an Intel/AMD machine. The pitch is cloud-like convenience without handing your data to the cloud.

- **[rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch)** — A free, open-source AI engineering curriculum spanning 20 phases and 523 lessons. Every lesson pairs the math with a from-scratch implementation before reaching for a framework, and each one ships a reusable artifact — a prompt, skill, agent, or MCP server.

- **[browser-use/jev-ultrafast](https://github.com/browser-use/jev-ultrafast)** *(tagged: Laya)* — A browser agent built around a dynamic, indexed action space: it enumerates what's actually actionable on the page and validates a target before firing, rather than generating text for every step. That drops browser protocol calls from ~1,092 to ~101 per task and finishes something like a flight search in ~7 seconds, with an agent loop under 200 lines. Very early though — 3 commits, and no shadow DOM, iframe, or complex keyboard support yet.

- **[simplifaisoul/osiris](https://github.com/simplifaisoul/osiris)** — A real-time OSINT dashboard that layers flight tracking, seismic data, public CCTV, conflict zones, and news feeds onto a single GPU-rendered map, pulling from a dozen free public APIs. It bills itself as a Palantir alternative, which oversells it — there's no private-data ingestion or ontology underneath — but as a dense live map mashup with an OSINT toolkit bolted on, it's a fun one to poke at.
