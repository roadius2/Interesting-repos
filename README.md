# Interesting Repos

A running list of GitHub projects I've stumbled across and found genuinely interesting, each with a quick note on why.

## The List

- **[incoai/splash](https://github.com/incoai/splash)** — A local inference engine built specifically for Apple silicon Macs that serves small language models to coding agents and API clients. Uses specialized kernels, draft models, and per-model memory management to get fast, competitive inference running entirely on-device.

- **[V380-Ori/Astris.Binaries](https://github.com/V380-Ori/Astris.Binaries)** — Prebuilt binaries for Astris, a Nintendo Switch emulator for Apple silicon Macs on macOS 15+. It picks up where Ryujinx left off and retargets it at modern Mac hardware, which is a nice example of the emulation community keeping a project alive by porting it somewhere new.

- **[RyanCodrai/turbovec](https://github.com/RyanCodrai/turbovec)** — A Rust vector search index implementing Google's TurboQuant algorithm, with Python bindings for RAG systems. The compression is the headline: 10M documents in 4GB instead of 31GB, while still beating FAISS on search speed via hand-written SIMD kernels, and it indexes online with no training phase.
