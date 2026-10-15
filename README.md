<h1 align="center">Hi 👋, I'm Malay Satapathy</h1>

<p align="center">
<img align="center" src="https://i.pinimg.com/originals/7b/4d/13/7b4d132727ca76f0b433b72769c67c06.jpg" alt="Welcome to my Github Page">
</p>

</br>

<h3 align="center">One man’s constant is another man’s variable</h3>

<p align="center">
  <strong>Product Deployed Engineer @ <a href="https://about.google/">Google</a></strong> &nbsp;·&nbsp; Product, Growth &amp; Applied AI
  <br/>
  <sub>
    <a href="https://linkedin.com/in/malaysatapathy">LinkedIn</a> &nbsp;·&nbsp;
    <a href="https://dev.to/malaysatapathy">DEV.to</a> &nbsp;·&nbsp;
    <a href="mailto:satapathymalay.95@gmail.com">satapathymalay.95@gmail.com</a> &nbsp;·&nbsp;
    <a href="https://instagram.com/malaysatapathy">Instagram</a> &nbsp;·&nbsp;
    <a href="https://fb.com/malaysatapathy">Facebook</a>
  </sub>
</p>

<br/>

I’m a **Product Deployed Engineer at Google**, working at the intersection of engineering, product strategy, and real-world systems deployment.

Outside of work, I spend an unreasonable amount of time studying a single problem: **why do frontier models fail on hard, multi-step engineering tasks—and what kind of cognitive scaffolding actually fixes them?** When I’m not poking at agent reasoning loops, context rot, or on-device models, I like building zero-latency browser tools, multiplayer web games, and 3D experiments.

---

### ⚡ Selected Work & Experiments

- **🧠 [metacog](https://github.com/malay-satapathy/metacog)** — *System-2 execution protocol for coding agents*  
  Smart models rarely fail on hard bugs from a lack of coding knowledge; they fail because they tweak the same broken line five times in a row instead of questioning their root premise. `metacog` wires epistemic calibration (`[KNOWN]` vs `[ASSUMED]`), competing-hypothesis falsification, adversarial red-teaming, and a **2-strike anti-thrashing circuit breaker** into Claude Code, Cursor, Antigravity, and Codex in ~100 lines.

- **🔥 [circle-of-shaq](https://github.com/malay-satapathy/circle-of-shaq)** — *Zero-leak serverless P2P social deduction game* &nbsp;·&nbsp; **[Play Live ↗](https://malay-satapathy.github.io/circle-of-shaq/)**  
  Started during game night when we opened the browser network tab on `spyfall.co` and noticed `is_spy: true` leaking in plaintext JSON to every player in the room (along with 11 other loopholes). Rebuilt from scratch with a zero-leak role engine, unified screen layouts so glancing at a phone reveals nothing, serverless WebRTC P2P (`PeerJS`) multiplayer, and a custom *Desi Adda & Shaadi* deck for 3–24+ players.

- **✨ [delim](https://github.com/malay-satapathy/delim)** — *`<1ms` client-side data studio with on-device AI* &nbsp;·&nbsp; **[Launch Studio ↗](https://malay-satapathy.github.io/delim/)**  
  Every online list-delimiter tool was covered in ads and sent production SQL IDs to a backend. `delim` runs 100% in-browser with zero network calls: paste any dataset and it auto-predicts the top 3 transformations in `<1ms`, supports `pandas`-style operations and dialect-aware SQL chunking (BigQuery `UNNEST`, Postgres `ANY`, Oracle `ORA-01795`), and uses Chrome’s on-device **Gemini Nano (`window.ai`)** for plain-English pipelines.

- **🕹️ [play-deck](https://github.com/malay-satapathy/play-deck)** — *Modular 22-game web arcade* &nbsp;·&nbsp; **[Launch Arcade ↗](https://malay-satapathy.github.io/play-deck/)**  
  An experiment in frontend plugin isolation: 22 classic and indie games (*Tetra-Drop*, *Maze-Muncher*, *Merge the Stack*, *Typing Defender*, *Quantum Dice*) architected as zero-collision encapsulated modules that share a single cross-game XP state machine and adapt automatically between desktop keyboards and mobile touch DPADs.

- **🌞 [threejs_react](https://github.com/malay-satapathy/threejs_react)** & **🌦️ [clime_weather_app](https://github.com/malay-satapathy/clime_weather_app)** — *Interactive 3D WebGL & React UI playgrounds* &nbsp;·&nbsp; **[3D Demo ↗](https://malay-satapathy.github.io/threejs_react/)** · **[Weather Demo ↗](https://malay-satapathy.github.io/clime_weather_app/)**  
  Explorations in 3D browser rendering with `Three.js`, `@react-three/fiber`, `drei`, and `cannon.js` physics alongside minimalist React interfaces.

---

### 📓 Field Notes

1. **Prompting is easy; step 18 of a tool chain is an architecture problem.** Context windows rot when unverified guesses and observed facts live side by side.
2. **First-idea bias breaks autonomous workflows.** Forcing an agent to write down two competing hypotheses—and run the fastest probe to *disprove* them—beats blind retries every time.
3. **If it can run in `<1ms` on the client, it doesn't need a server.** Between modern browser APIs, WebRTC P2P, and on-device models, most developer utilities have no business touching a backend.
4. **Beyond the terminal:** Always happy to chat about **system design, applied AI, product strategy, travel, food**—or trade top-tier **memes** 🎃.

---

### 🛠️ Toolbox

<p align="left">
  <img src="https://skillicons.dev/icons?i=gcp,ts,react,nextjs,threejs,python,java,nodejs,postgres,mongodb,git,githubactions&perline=12" alt="Tech Stack" />
</p>

<sub>
  <strong>Daily drivers &amp; ecosystem:</strong> TypeScript · React · Next.js · Python · Java · Google Cloud &amp; BigQuery · Agent Protocols (MCP / SKILL.md) · On-Device AI · Three.js / WebGL · Node.js · Git &amp; CI/CD
</sub>

<br/><br/>

<p align="right">
  <img src="https://komarev.com/ghpvc/?username=malay-satapathy&label=Profile%20views&color=64748b&style=flat-square" alt="Profile views" />
</p>
