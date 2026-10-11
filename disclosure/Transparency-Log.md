# 🔎 Transparency Log: MATH 140 Proof Garden

**Course:** DIGI 230 Ethics of Emerging Technology · **Client course:** MATH 140 The Geometry of Physical Space

This is **file 2 of 2**. It holds the **research, sources, every AI session and prompt, and every output** (AI 101 parts 2, 3, 4 and 5).
File 1 is [AI Use Disclosure](AI-Use-Disclosure.md) (summary, intent, decisions, statement).

## 🔬 02 · Research Brief

### ❓ Research question
Can a **hints-only** AI help students fix proofs **without** hurting their learning?

### ✅ Short answer
**Yes, with guardrails.** Open AI can **hurt** test scores. Hints-only AI did **not** hurt scores. But AI **often gets proofs wrong**. So a **person** must check unsure hints, and only a person grades.

### 1️⃣ Claim: "Any AI help makes students learn more."
- 🔍 **We checked:** Bastani et al. (2025), *PNAS*.
- 📄 **The source says:** open ChatGPT raised practice scores **48%**. Then scores were **17% lower** on the real test. A hints-only tutor did **not** lower scores.
- 🔄 **Result:** **Changed.** Our helper gives **hints only**.

### 2️⃣ Claim: "A good AI tutor can teach well."
- 🔍 **We checked:** Kestin et al. (2025), *Scientific Reports*.
- 📄 **The source says:** a teacher-built AI tutor gave **larger learning gains** than an active-learning class.
- ⚠️ **Result:** **Supported, with a limit.** The study is about **physics**, not geometry. *(guess)*

### 3️⃣ Claim: "AI can check if a proof is correct."
- 🔍 **We checked:** Petrov et al. (2025), arXiv.
- 📄 **The source says:** most AI models scored **under 5%** on full contest proofs, graded by experts.
- ❌ **Result:** **Contradicted.** The AI **never** says "correct". It **never** grades.

### 4️⃣ Claim from our own test: "The helper never gives too much."
- 🔍 **We checked:** our live test, Oct 1 (3 runs).
- 📄 **We saw:** 1 hint named the exact rule (CPCTC).
- ⚠️ **Result:** **Partly contradicted.** We changed the practice hints. We plan **20 more tests**.

## 🔎 03 · Source Verification Log

### 📚 Research sources
#### Source 1
- **Who:** Bastani, H., Bastani, O., Sungu, A., Ge, H., Kabakcı, Ö., Mariman, R.
- **Title:** Generative AI without guardrails can harm learning: Evidence from high school mathematics
- **Where / when:** *PNAS* 122(26), June 2025
- **Link:** https://doi.org/10.1073/pnas.2422633122
- **How we checked:** the DOI record on Crossref (Sept 29, 2026). The 48% / 127% / 17% numbers checked against the PubMed and Wharton summaries.

#### Source 2
- **Who:** Kestin, G., Miller, K., Klales, A., Milbourne, T., Ponti, G.
- **Title:** AI tutoring outperforms in-class active learning
- **Where / when:** *Scientific Reports* 15, 17458, June 2025
- **Link:** https://doi.org/10.1038/s41598-025-97652-6
- **How we checked:** the DOI record on Crossref (Sept 29, 2026).

#### Source 3
- **Who:** Petrov, I., Dekoninck, J., and others
- **Title:** Proof or Bluff? Evaluating LLMs on 2025 USA Math Olympiad
- **Where / when:** arXiv:2503.21934, March 2025 (revised Sept 2025)
- **Link:** https://arxiv.org/abs/2503.21934
- **How we checked:** the arXiv abstract page (Sept 29, 2026).

### 🗂️ Class and tool sources
| # | Source | Used for | Checked |
|---|---|---|---|
| **1** | DIGI 230 site: course map brief, how-to guide, M1 page, schedule | Rules and due dates | Read on the site, Sept 24 – Oct 6 |
| **2** | DIGI 230 build pack (PRD, ARD, checklist, handoff, tests) | The M3 build plan | Read the zip, Oct 6 |
| **3** | MATH 140 syllabus (Weeks 1–10) | Week numbers | From our note [MATH 140 Course Map - Unified](https://github.com/cornishlikeadam/math140-course-map/blob/main/notes/06%20Disclosure/../MATH%20140%20Course%20Map%20-%20Unified.md) |
| **4** | OpenCode Zen docs and model list | Free AI models | Read Oct 1 |
| **5** | OpenRouter docs | Tried, then **dropped** | Read Sept 24 |

### 🗑️ Sources we removed
| Source | Why it was used | Why it was removed |
|---|---|---|
| Lewis et al. (2020), *Indigenous Protocol and AI* | SUST 720 map | The team **removed** the Indigenous content (Sept 24). |
| Carroll et al. (2020), *CARE Principles* | SUST 720 map | Same reason. |
| Tetlock & Gardner (2015), *Superforecasting* | SUST 720 map | The client course **changed** to MATH 140. |
| Cummings (2017) and Bainbridge (1983) | SUST 720 deskilling claim | **Not verified.** The course changed. |

### ✅ Claim check
| Claim | Source says | Status | Action |
|---|---|---|---|
| Open AI helps learning | Lower test scores (−17%) | ❌ Contradicted | **Hints only** |
| AI tutors help | Larger gains (physics) | ⚠️ Supported, limited | **1 question back**, test in geometry |
| AI can check proofs | Under 5% on full proofs | ❌ Contradicted | **No AI grading** |
| Exams have no computers | Syllabus says **open book** | ⚠️ Unclear | **Ask the professor** ([Professor Interview Kit](https://github.com/cornishlikeadam/math140-course-map/blob/main/notes/06%20Disclosure/../Professor%20Interview%20Kit.md)) |

## 🤖 04 · AI Use Log

**Student:** KJ Cornish · **Course:** DIGI 230 · **Term:** Fall 2026
This log is **append-only**. We add corrections as new lines.

### 🗓️ Sessions
| # | Date | Work | Tool / model | What the AI did | Extent |
|---|---|---|---|---|---|
| **1** | Sept 24 | SUST 720 map + chat | Claude (Claude Code desktop) | Built the map, PDF, site, and chat. Wrote prompts. | **Substantial** |
| **2** | Sept 24 | Chat model | OpenCode Zen (Space Bunny) | Answers inside the Stress-test chat | **Product feature** |
| **3** | Sept 29 | MATH 140 map | Claude | Checked sources. Built the map and Proof check tutor. | **Substantial** |
| **4** | Oct 1 | M2 + revision | Claude | Drafted the M2 proposal. Ran 3 live tests. | **Substantial** |
| **5** | Oct 1 | Hints | OpenCode Zen (Space Bunny, Big Pickle, MiMo) | Answers inside the Proof check tutor | **Product feature** |
| **6** | Oct 6 | M3 build | Claude | Wrote all prototype code. Ran 16 + 15 checks. | **Substantial** |
| **7** | Oct 6 | Redesign + videos + guide | Claude | Wrote code, notes, 8 videos, and this folder | **Substantial** |

> [!NOTE]
> 🧑‍🎓 **What we did ourselves:** picked the course. Named the people. Set the rules. Removed content. Picked the providers. Asked for each change. Added the real syllabus. Approved each step.

### 💬 Every prompt (short version)
| # | Date | Our prompt (short) | What the AI did |
|---|---|---|---|
| **P1** | Sept 24 | Map SUST 720 from our stakeholder PDF and the course map brief. Complete all steps. | Built the SUST 720 map, PDF, and artifact. |
| **P2** | Sept 24 | Remove the Indigenous part. Give me a prompt to develop this. Push to GitHub with a working link. | Removed content, wrote PROMPT.md, made a GitHub repo and page. |
| **P3** | Sept 24 | Stop before GitHub. Give me 4 common and 4 uncommon prompts. | Repo was already public. Wrote 8 prompts. |
| **P4** | Sept 24 | Make the prompts for Claude Design (copy and paste). | Rewrote 8 prompts for Claude Design. |
| **P5** | Sept 24 | Give me the link. Make it a Vercel site. | Deployed to Vercel. |
| **P6** | Sept 24 | Add a text box so students can process ideas through chat. | Added the Stress-test chat (Claude API). |
| **P7** | Sept 24 | The API key does not work. Can I use a free model like OpenRouter? | Switched the chat to OpenRouter free models. |
| **P8** | Sept 24 | Same rejection for OpenRouter. | Found the key was not saved. Gave steps. |
| **P9** | Sept 24 | Also upload it to a GitHub repo. | Confirmed the repo was up to date. |
| **P10** | Sept 24 | I'm going to use OpenCode instead. | Added AGENTS.md for OpenCode. |
| **P11** | Sept 24 | How to add it? / What is "value"? / It's added. | Gave key steps. Found the wrong provider. |
| **P12** | Sept 24 | It is supposed to be OpenCode. Why did you change it? | Switched the chat to OpenCode Zen. It worked. |
| **P13** | Sept 24 | Why is the response time so slow? | Cut reply time from ~53 s to ~9 s. |
| **P14** | Sept 24 | Log what the tool does, should do, does not do, and what the human does. | Added a transparency log. Marked the chat as not meeting its goal. |
| **P15** | Sept 29 | Change the client course to MATH 140. | Built the MATH 140 map and the Proof check tutor. |
| **P16** | Sept 29 | Organize it into 3 pages in Obsidian. | Wrote 3 Obsidian notes. |
| **P17** | Oct 1 | Fill out the M2 template. Make a crucial revision. Give the map and stakeholders their own pages. | Wrote the M2 proposal. Added the 48-hour teacher review. |
| **P18** | Oct 1 | Give me the steps to add the key. / I can't find the form. / (screenshot) | Gave key steps for the Vercel UI. |
| **P19** | Oct 1 | I added it. Check it. Tell me what was updated. Put it in the folder. | Tested 3 runs. Logged results in Obsidian. |
| **P20** | Oct 1 | A 10-year-old must understand it, with the nuance. | Added Simple words mode and Big ideas. |
| **P21** | Oct 1 | Simplify the whole folder for a 10-year-old. | Rewrote all notes. Archived the long ones. |
| **P22** | Oct 6 | Start the build. Explain it simply. Plan it for 8-year-olds. Use the build pack. | Built the practice helper. Ran 16 checks. Wrote the build folder. |
| **P23** | Oct 6 | New look: white, pink, blue, cyan. Calligraphy. Fruits. Emojis. Obsidian tool on the site. ASD-STE100. | Redesigned all pages. Built the Garden Guide and sync script. |
| **P24** | Oct 6 | Add 3Blue1Brown-style explainer videos as a pop-up and in the README. | Made 5 code-drawn videos. Added the pop-up and GIFs. |
| **P25** | Oct 6 | Make a disclosure (AI 101 order), an interview kit, a white paper, metrics, a quick syllabus, and SCADpro pitch ideas. | Made this folder, the interview kit, the white paper, and 3 more videos. |
| **P26** | Oct 11 | Rebuild the repo so it fits the same folders as the DIGI 230 repo, under 18 files, with 2 disclosure files. Keep the site and the tool working. Connect it back. | Made `math140-course-map-lite`: 14 files, 6 folders. Merged 5 explainers into 1 file and 8 disclosure pages into these 2. Linked both repos. |

> [!TIP]
> 📝 **26 rows cover about 31 messages.** Some short follow-ups are grouped in 1 row. The full prompts are in the chat history. These short versions keep the **meaning**. They do not keep every word.

## 🧪 05 · Outputs: Runs and Revisions

### 📦 What we made
| # | Output | Link |
|---|---|---|
| **1** | 🗺️ MATH 140 map (Simple words + Full detail) | https://math140-course-map.vercel.app |
| **2** | 💧 Proof check tutor (live AI, hints only) | https://math140-course-map.vercel.app (bottom of the map) |
| **3** | 🧪 Practice helper (pretend hints) | https://math140-course-map.vercel.app/prototype/ |
| **4** | 📗 Garden Guide (Ask box + 48 answers in tabs) | https://math140-course-map.vercel.app/guide/ |
| **5** | 🎬 8 explainer videos | https://math140-course-map.vercel.app (pop-up) |
| **6** | 📄 M1 PDF | `~/Downloads/TeamName_M1_CourseMap.pdf` |
| **7** | 💻 Code | https://github.com/cornishlikeadam/math140-course-map |
| **8** | 🗄️ Old SUST 720 map | https://sust720-course-map.vercel.app |
| **9** | 🪶 Slim repo (same site + tool) | https://github.com/cornishlikeadam/math140-course-map-lite |

### 🔁 Runs and revisions
| # | Run | What went wrong | What we changed |
|---|---|---|---|
| **1** | SUST 720 map v1 | Indigenous content not wanted | **Removed** it |
| **2** | Chat on Claude API | No working key | Tried **OpenRouter** |
| **3** | Chat on OpenRouter | The key was an **OpenCode** key | Switched to **OpenCode Zen** |
| **4** | OpenCode chat | Replies took **~53 s** | Lower thinking effort: **~9 s** |
| **5** | SUST Stress-test chat | No number work. **Did not meet its goal.** | Added an honest **transparency log** |
| **6** | MATH 140 map v1 | Only the student checked hints | **Teacher checks unsure hints in 2 days** |
| **7** | Live hint test 1 | Named the exact rule (CPCTC) | Practice hints now point back to step 5 |
| **8** | Too many words | Hard for kids to read | **Simple words** mode + rewritten notes |
| **9** | Practice helper v1 | Start over clears a stop | **Still open.** Fix next. |
| **10** | Redesign | Generic look | White, pink, blue, cyan. Garden theme. Videos. Guide. |
| **11** | Long pages | Too much on the screen. The tool was hard to find. | **Closed tabs** on the map and the Guide. Notes reader removed. **💧 Hint tool** link in the menu. |

### 🧪 Test totals
- **3** live hint tests (Oct 1): 2 pass, 1 close call.
- **16** practice checks (Oct 6): 16 pass.
- **15** re-run checks (Oct 6, new look): 15 pass.
- **1** known hole: open.
