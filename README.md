# 🪶 Proof Garden Lite: MATH 140 + AI

![Class](https://img.shields.io/badge/DIGI_230-Ethics_of_Emerging_Tech-FF5FA2?style=for-the-badge) ![Client](https://img.shields.io/badge/Client-MATH_140_Geometry-2F5BFF?style=for-the-badge) ![AI](https://img.shields.io/badge/AI-Stop_3_only-22D3EE?style=for-the-badge)

> [!IMPORTANT]
> **Our project in 1 sentence:** we found the **1 safe place** for an AI helper in a geometry class. We also found where AI must **stay out**.

> [!NOTE]
> 🪶 This is the **slim copy** of our main DIGI 230 repo, **[math140-course-map](https://github.com/cornishlikeadam/math140-course-map)**. It has the **same site** and the **same hint tool** in **14 files**. The main repo keeps the full notes and the video files.

## 🔗 Open it
| # | Page | Link |
|---|---|---|
| **1** | 🗺️ **The map** | https://math140-course-map.vercel.app |
| **2** | 🧪 **The practice helper** | https://math140-course-map.vercel.app/prototype/ |
| **3** | 📗 **The Garden Guide** | https://math140-course-map.vercel.app/guide/ |
| **4** | 💧 **The hint tool** (live AI, hints only) | https://math140-course-map.vercel.app/#tool |
| **5** | 🌸 **The main repo** | https://github.com/cornishlikeadam/math140-course-map |

## 🎬 Watch the 5 parts
Each video is about **20 seconds**. The site plays them from [`explainers/index.html`](explainers/index.html). The GIFs below come from the main repo.

| # | Part | Video |
|---|---|---|
| **1** | 🌱 **Seed: Draw by hand.** **No AI.** | ![Part 1](https://raw.githubusercontent.com/cornishlikeadam/math140-course-map/main/explainers/media/part1.gif) |
| **2** | 🌿 **Sprout: Write your proof.** **No AI.** | ![Part 2](https://raw.githubusercontent.com/cornishlikeadam/math140-course-map/main/explainers/media/part2.gif) |
| **3** | 💧 **Water: Get 1 hint.** **The only AI part.** | ![Part 3](https://raw.githubusercontent.com/cornishlikeadam/math140-course-map/main/explainers/media/part3.gif) |
| **4** | 🌸 **Bloom: Explain out loud.** **No AI.** | ![Part 4](https://raw.githubusercontent.com/cornishlikeadam/math140-course-map/main/explainers/media/part4.gif) |
| **5** | 🍓 **Fruit: Show what you know.** **Only the teacher grades.** | ![Part 5](https://raw.githubusercontent.com/cornishlikeadam/math140-course-map/main/explainers/media/part5.gif) |

## 📜 Disclosure (2 files)
1. 📜 [**AI Use Disclosure**](disclosure/AI-Use-Disclosure.md): the summary, our intent, our decisions, and the statement.
2. 🔎 [**Transparency Log**](disclosure/Transparency-Log.md): research, sources, **every prompt**, and every output.

## 📁 What is in here
| Folder / file | What it does |
|---|---|
| `index.html` | 🗺️ The map and the 💧 Proof check tool |
| `api/proof-check.js` | 🤖 The tool's server part (Meta Llama 3.3 70B (open-weight) through Vercel AI Gateway) |
| `assets/` | 🎨 Colors, fonts, menu, and the video pop-up |
| `explainers/index.html` | 🎬 All 5 videos, drawn in code |
| `guide/` | 📗 The Garden Guide and its 48 answers (no AI) |
| `prototype/index.html` | 🧪 The practice helper (pretend hints, no AI) |
| `disclosure/` | 📜 The 2 disclosure files |

## ▶️ Run it on your computer
1. Open a terminal in this folder.
2. Run `python3 -m http.server 8765`.
3. Open http://127.0.0.1:8765.
4. ⚠️ The 💧 hint tool needs the server part. It works when deployed on Vercel. It does **not** work with the simple server.

## 🔑 The hint tool connection
1. Vercel sends the deployed function a short-lived OIDC token with each request.
2. No long-lived provider key is stored in this repo.
3. A non-Vercel host needs `AI_GATEWAY_API_KEY`.
