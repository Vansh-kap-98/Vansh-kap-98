<div align="center">

<a href="https://vansh-webdev-portfolio.vercel.app/">
  <img alt="Vansh Kapoor" src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=700&size=28&pause=1100&color=A78BFA&center=true&vCenter=true&width=700&height=64&lines=Hi%2C+I'm+Vansh+%F0%9F%91%8B;Full-stack+%2B+AI%2FML+%E2%80%94+Manipal+Jaipur;Open-source+C%2B%2B+contributor;C%2B%2B+at+the+bottom%2C+WebGL+at+the+top;40-70%25+faster+is+a+good+day" />
</a>

<p>
  <a href="https://vansh-webdev-portfolio.vercel.app/"><img alt="portfolio" src="https://img.shields.io/badge/portfolio-A78BFA?style=for-the-badge&logo=vercel&logoColor=white&labelColor=0D1117" /></a>
  <a href="https://www.linkedin.com/in/vansh-kapoor-03a7572a7/"><img alt="linkedin" src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117" /></a>
  <a href="mailto:v.ansh.kap.004@gmail.com"><img alt="email" src="https://img.shields.io/badge/email-EA4335?style=for-the-badge&logo=gmail&logoColor=white&labelColor=0D1117" /></a>
  <img alt="location" src="https://img.shields.io/badge/Jaipur,_IN-0D1117?style=for-the-badge&logo=googlemaps&logoColor=A78BFA" />
</p>

<p>
  <a href="https://github.com/Vansh-kap-98?tab=followers"><img alt="followers" src="https://img.shields.io/github/followers/Vansh-kap-98?label=followers&style=flat-square&color=A78BFA&labelColor=0D1117" /></a>
  <img alt="stars" src="https://img.shields.io/github/stars/Vansh-kap-98?label=stars&style=flat-square&color=A78BFA&labelColor=0D1117" />
  <img alt="profile views" src="https://komarev.com/ghpvc/?username=Vansh-kap-98&style=flat-square&color=A78BFA&label=profile+views" />
</p>

</div>

---

I write code at both ends of the stack: **memory allocators in C++** and **shaders in the browser**.
I care about understanding systems deeply, not just shipping features.

- 🎓 B.Tech CSE (AI & ML), Manipal University Jaipur — 2023–2027
- 🧩 Open-source contributor to [`sourcemeta/core`](https://github.com/sourcemeta/core) and [`sourcemeta/blaze`](https://github.com/sourcemeta/blaze) — mimalloc integration and direct dispatch for array assertions
- 🌍 Leading the Indian team on **Cash Compass**, an international collab with Southern Federal University (Taganrog, Russia)
- 🔬 StyleGAN2-ADA work on medical imaging data scarcity, presented at **AIC 2026**
- 💼 Open to SWE internships and freelance 3D web work
- 🎧 Learning Japanese, producing music, designing gameplay systems

```
now        →  Architecture Lead, Cash Compass · OSS contributor, Sourcemeta Core & Blaze
building   →  Release Radar — BYOK AI changelog generator (Electron)
researching→  StyleGAN2-ADA for medical imaging data scarcity
ask me     →  CMake pain, allocator benchmarks, why your Three.js scene drops frames
```

---

### <samp>🧰 Tech Stack</samp>

<p>
  <img alt="stack" src="https://skillicons.dev/icons?i=cpp,python,ts,js,react,threejs,flutter,dart,electron,nodejs,flask,django,postgres,mongodb,supabase,tensorflow,docker,cmake,git,githubactions,unity,vercel&perline=11" />
</p>

<details>
<summary><sub>full list, with the things that have no icon</sub></summary>
<br />

**Languages** — C++, Python, JavaScript (ES6+), TypeScript, SQL, Dart
**Frontend** — React, Three.js, WebGL, Flutter
**Backend & data** — Node.js, Flask, Django, REST APIs, MySQL, PostgreSQL, MongoDB, Supabase
**AI/ML** — PyTorch, TensorFlow, scikit-learn, HuggingFace Transformers, RAG pipelines, FAISS
**Build & DevOps** — CMake, Docker, Git, GitHub Actions, Vercel, Google Benchmark

</details>

---

### <samp>📌 Featured Work</samp>

<table>
<tr>
<td width="50%" valign="top">

**⚡ [mimalloc in Sourcemeta Core](https://github.com/sourcemeta/core/pull/2708)**
<sub>Merged PR #2708 · ~30 C++ libraries</sub>

Integrated the mimalloc allocator across the CMake build for Linux — **40–70% latency improvement**
on 10-run aggregated Google Benchmark suites. Diagnosed an export-set collision and a
sanitizer/allocator CI crash on the way; verified in Docker across static and shared builds.
Follow-up: [`blaze` PR #975](https://github.com/sourcemeta/blaze/pull/975), direct dispatch for array assertions.

<sub>`C++` `CMake` `Docker` `Google Benchmark`</sub>

</td>
<td width="50%" valign="top">

**🩻 [Synthetic Chest X-rays](https://github.com/Vansh-kap-98/stylegan-pneumonia)**
<sub>StyleGAN2-ADA · 256×256 · presented at AIC 2026</sub>

Class-conditional pipeline: 8-layer mapping network, AdaIN, adaptive discriminator augmentation,
R1 regularization. **FID 25.30 / KID 0.02** on 5,232 samples — enough fidelity to push a downstream
VGG16 pneumonia classifier to **97.99%** accuracy.

<sub>`PyTorch` `GANs` `Medical Imaging`</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**📝 Release Radar**
<sub>Electron + React desktop app</sub>

Turns any GitHub commit/tag range into a publish-ready changelog. **BYOK across 4 providers**
(Anthropic, OpenAI, Groq, Gemini). Keys encrypted at rest in the OS keychain via Electron
`safeStorage`; sandboxed renderer with zero direct filesystem or network access. The core pipeline
is Electron-free and reused unmodified in a companion GitHub Action.

<sub>`Electron` `React` `LLM APIs` `AppSec`</sub>

</td>
<td width="50%" valign="top">

**💰 [Cash Compass](https://cash-compass-smoky.vercel.app/)**
<sub>Architecture Lead · India ⇄ Russia</sub>

Cross-platform expense tracker: React/TypeScript dashboard and a Flutter mobile app over one shared
Supabase backend, with on-device OCR receipt parsing and real-time balance sync. I own the system
design and direct the Indian dev team, working with the Institute of Computer Technologies and
Information Security in Taganrog.

<sub>`TypeScript` `Flutter` `Supabase` `OCR`</sub>

</td>
</tr>
</table>

<details>
<summary><b><samp>Client work — 3D interactive web (V-Design)</samp></b></summary>
<br />

Three shipped, deployed sites in React + Three.js + WebGL, ₹30,000 in client revenue. Work went into
reusable component architectures and getting immersive scenes to hold their frame budget on mid-range hardware.

| Site | What it is |
| --- | --- |
| [anotherskyexplore.com](https://www.anotherskyexplore.com/) | Travel brand, 3D hero experience |
| [ICCAIML '26](https://iccaiml-26-main.vercel.app/) | International conference site |
| [Portfolio](https://vansh-webdev-portfolio.vercel.app/) | My own playground |

</details>

---

### <samp>📊 The Numbers</samp>

<div align="center">

<img alt="stats" width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=Vansh-kap-98&theme=github_dark" />
<img alt="repos per language" width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=Vansh-kap-98&theme=github_dark" />
<img alt="most committed language" width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=Vansh-kap-98&theme=github_dark" />
<img alt="productive time" width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=Vansh-kap-98&theme=github_dark&utcOffset=5.5" />

<img alt="streak" src="https://streak-stats.demolab.com?user=Vansh-kap-98&theme=github-dark-blue&hide_border=true&background=0D1117&ring=A78BFA&fire=A78BFA&currStreakLabel=A78BFA&sideLabels=C9D1D9&dates=8B949E" />

</div>

---

### <samp>🌍 Contribution World</samp>

<div align="center">
  <img alt="Contribution World — pixel-art terrain built from my contribution graph, with a miner walking across it" src="./contribution-world.svg?v=2" width="900" />
</div>

<sub>Each column is a day; stack height is that day's contribution count. The miner works the whole year on a 19s loop — walking, swinging a pickaxe and breaking the top block of each day it steps on, hopping gaps and climbing onto peaks, and sitting down to rest on the tall ones. Sun and moon cross behind it on a 20s day/night cycle. Peaks are flagged with what shipped there: ⚔️ game dev, ⚙️ Release Radar, 🧪 StyleGAN2-ADA, 📕 sourcemeta C++.</sub>

<details>
<summary><b><samp>🎓 Credentials & coursework</samp></b></summary>
<br />

**Education** — B.Tech CSE (AI & ML), Manipal University Jaipur, 2023–2027 · CGPA 7.96 (through 6th sem)

**Certifications** — Microsoft Azure AI Fundamentals · Oracle SQL · Red Hat DBMS · NPTEL (Machine Learning, DAA, Deep Learning)

**Achievement** — National Qualifier, Smart India Hackathon 2025

**Also** — Student Placement Coordinator for the AIML department, running employer outreach for 300+ students.

</details>

<details>
<summary><b><samp>🎧 Away from the keyboard</samp></b></summary>
<br />

Learning Japanese, producing music and playing instruments, designing game strategy and gameplay
systems, and poking at 3D web ideas that have no business case whatsoever. A surprising amount of my
product instinct comes from the game design side.

</details>

<div align="center">
<br />
<sub><i>⭐️ Always open to interesting problems — <a href="mailto:v.ansh.kap.004@gmail.com">say hi</a>.</i></sub>
</div>
