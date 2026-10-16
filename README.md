## Mehdi Zenati

AI Software Engineer, Paris. TypeScript from the browser to the runtime.

I build LLM-based products that reach production and stay there. Day to day that means
agent orchestration with LangGraph, RAG and CAG pipelines (including a retrieval engine
written without a framework, because chunking and vectorization were worth keeping under
direct control), MCP servers, Amazon Bedrock and Vertex AI. Full-stack around it:
Angular, Vue, Node. Rust when the app has to talk to the operating system.

I'm also the deployment referent for my entity at Devoteam AI Apps (~25 people) and the
one application-security topics get forwarded to.

### 🔧 What's public here

**[monitor4me](https://github.com/MehdiZen/monitor4me)**: hardware monitoring dashboard
for Windows. Tauri 2 shell, TypeScript UI, a Node collector polling LibreHardwareMonitor
every 2s into InfluxDB. Z-score anomaly detection on thermal throttling, GPU clock drops
and PSU rail instability, plus electricity cost tracking. Signed installer and
auto-updater. The README documents what the sensors *can't* tell you as much as what
they can (no AM5 RAM sensor, RAPL under-reads by ~7%).

**[legion4me](https://github.com/MehdiZen/legion4me)**: a personal AI assistant that runs
entirely on your own machine. Personas and on-demand agents on top of local models served
by Ollama, with a persistent memory extracted after each exchange and long conversations
compacted step by step. Several personas can share one conversation, each with its own
memory context. Tool calling for web search, page fetching and YouTube transcripts.
Node and TypeScript backend on SQLite, Vue 3 frontend.

**[deck4me](https://github.com/MehdiZen/deck4me)**: a Windows app for streamers. It reads
the webcam, recognizes face and hand poses with MediaPipe running locally and offline, and
fires memes, macros and actions when you hold a pose. Tauri v2 shell, Angular studio, a
local axum server feeding an OBS overlay, and a virtual camera built on softcam. A
recording wizard learns each pose from three short takes and refuses poses that are too
close to each other.

**[apply4me](https://github.com/MehdiZen/apply4me)**: a browser extension for job
seekers. One click on a posting tells you whether it is worth your time, then it prepares
a one-page CV and a cover letter from a base of facts you reviewed. The code computes the
verdict and checks the numbers, tools and seniority in what the model writes, the model
only extracts and rephrases. You bring your own API key.

These four are source-available: free for personal use, with a paid license for
commercial use. Each README has a recorded demo on fictional data.

Most of what I write is client code or not released yet, so this account is thinner than
my week is. What is here, I document properly.

### 📫 Elsewhere

- [tisseurduweb.com](https://www.tisseurduweb.com): portfolio, an interactive 3D scene
  in Three.js with hand-written GLSL shaders and a satirical newspaper for a bio page
- [malt.fr/profile/mehdizenati](https://www.malt.fr/profile/mehdizenati): freelance,
  website design and integration

---

<sub>The previous version of this file defined a software methodology named after me. It
is still in the git history, where it belongs.</sub>
