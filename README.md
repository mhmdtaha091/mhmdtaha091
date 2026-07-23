# Muhammad Taha Khan

I build AI agent systems and the tooling that measures them — LLM agents, RAG pipelines, and the eval harnesses that keep them honest. My stack leans toward **LangGraph, MCP servers, FastAPI, and local/quantized inference** — whatever puts a measured, working system in front of a user.

---

## What I'm building

**[PentestAI](https://github.com/mhmdtaha091/PentestAI)** — autonomous web-pentest agent that runs entirely on consumer hardware. LangGraph orchestrator, **23-tool MCP server**, HippoRAG knowledge graph over OWASP / MITRE ATT&CK / CVE, and 35 in-house scanners, driving a fine-tune-free **Qwen2.5-Coder-14B on 12 GB VRAM**. On the DVWA benchmark it clears every Low and Medium module and covers **84.6% at High** — a local-model niche no published peer occupies.

**[Flight Recorder](https://github.com/mhmdtaha091/flight-recorder)** — local-first tracing, replay, and eval harness for AI agents. Records every LLM call, tool call, token, cost, and latency; replays runs deterministically against a keyed store; scores outputs against golden suites and flags regressions between versions. Built because most "agent" projects collapse the moment you measure them honestly.

**[SignBridge](https://github.com/mhmdtaha091/SignBridge)** — bilingual (ASL + PSL) sign-language tutor running entirely in the browser. MediaPipe hand landmarks + a TF.js temporal model recognize signs **on-device — no camera data leaves the machine** — with a three.js 3D avatar tutor that scores your form via dynamic time warping. **[▶️ Live demo](https://signbridge-kappa.vercel.app)**

**[BugScout](https://github.com/mhmdtaha091/bugscout)** — autonomous web QA agent. Crawls a site, discovers user flows, detects functional and accessibility bugs (axe-core), and emits **deterministic Playwright regression suites** — byte-identical output for the same input. MCP-native.

---

## Currently working on

- **Benchmarking PentestAI** against the published auto-pentest landscape (PentestGPT, VulnBot, CHECKMATE, XBOW) using the methodology in [`docs/research.md`](https://github.com/mhmdtaha091/PentestAI/blob/main/docs/research.md).
- **Flight Recorder** — dogfooding the harness across my own agents to build a reproducible eval baseline.
- **SignBridge PSL** — extending the Pakistan Sign Language dataset and the cross-source generalization study.

---

📫 [mhmdtahakhan0@gmail.com](mailto:mhmdtahakhan0@gmail.com)
