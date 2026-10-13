# 🪶 Proof Garden Lite: MATH 140 Interactive Course Map

A slim copy of [math140-course-map](https://github.com/cornishlikeadam/math140-course-map) (the main DIGI 230 repo). Same site, same Proof check tool, 14 files in 6 folders. The main repo keeps the Obsidian notes, the sync scripts, the 3 extra explainers and the rendered MP4/GIF media.

- **Live site:** https://math140-course-map.vercel.app (deployed from the main repo)
- **Main repo:** https://github.com/cornishlikeadam/math140-course-map
- **This repo:** https://github.com/cornishlikeadam/math140-course-map-lite

## 📁 Files
- `index.html`: the whole page as one file, with no build step. The course data lives in the `R` (steps), `P` (people) and `CARDS` (evidence) arrays in the script at the bottom, and the SVG map is drawn from those. The simple-words text lives in `K`.
- `api/proof-check.js`: a Vercel function behind the Proof check hint tutor. It calls Meta Llama 3.1 8B (open-weight) through Vercel AI Gateway, opts out of prompt training, and authenticates with Vercel’s short-lived OIDC request token (or `AI_GATEWAY_API_KEY` outside Vercel).
- `prototype/index.html`: the M3 practice helper. It uses simulated hints and makes no AI calls.
- `guide/index.html` + `guide/qa.json`: the Garden Guide. It answers questions from `qa.json` by keyword matching (no AI). "Open the note" links go to `notes/` in the main repo.
- `explainers/index.html`: all 5 canvas explainers plus the engine in one file. Open `explainers/index.html?n=1` … `?n=5`. It replaces the main repo's `1.html`–`5.html` + `engine.js`.
- `assets/garden.css` + `assets/garden.js`: the shared palette, fonts, top menu and video pop-up.
- `disclosure/AI-Use-Disclosure.md` + `disclosure/Transparency-Log.md`: the full AI 101 disclosure, merged from the main repo's 8-file `notes/06 Disclosure/`. The log is append-only.

## 🔁 Keeping the two repos in sync
- Site or tool change: make it in the main repo first, then copy the same file here (`index.html`, `api/`, `assets/`, `guide/`, `prototype/` are identical copies).
- Exception: `assets/garden.js` here points the pop-up at `explainers/index.html?n=`; the main repo uses `explainers/N.html`.
- Disclosure change: edit `notes/06 Disclosure/` in the main repo (via the Obsidian vault), then mirror it into the 2 files here.

## 🎨 Style rules (Oct 6, 2026)
- **Palette:** white, strawberry pink `#FF5FA2`, blueberry blue `#2F5BFF`, and water cyan `#22D3EE` used sparingly. Cyan means AI, pink means "no AI here", blue means a person decides.
- **Fonts:** Fondamento (calligraphy) for headings only; Lexend for all reading text.
- **Garden theme:** 🌱 Seed = Draw · 🌿 Sprout = Write · 💧 Water = Hint (AI) · 🌸 Bloom = Explain · 🍓 Fruit = Quiz. The teacher is the 🧑‍🌾 gardener and the partner is the 🐝 bee.
- **Writing:** ASD-STE100 style, so an 8-year-old can read it. Short sentences, one idea each, active voice, numbered steps, emojis and **bold** on the key words.

## 📏 Rules the map encodes (don't break these)
- AI is used in one place only: Step 3, Proof check. It is hint-only: one gap per reply, and it never writes a statement or reason. It only responds to a student draft of 2 or more steps.
- The student marks each hint Agree, Not sure or Disagree. The instructor reviews every Not sure or Disagree hint within 48 hours, before the Step 4 defense, and is accountable for wrong hints. (Revision of Oct 1: a struggling student is not the last check on a hint.)
- Steps 1 (Construct) and 4 (Defend) are non-use boundaries.
- Steps 1, 2, 4 and 5 are preserve-human-judgment zones. The instructor grades everything.
- The non-AI alternative is a printed justification checklist plus office hours.
- The page has two reading levels: "Simple words" (default, written so a 10-year-old can follow it, including the nuance) and "Full detail". Any content change must be made in both: static HTML pairs use `.m-s` / `.m-f`, and the map and step text live in the `K` (simple) and `R` (full) objects. The PDF is exported from `index.html#full`.
- The unit steps are assumptions built from the catalog description; confirm them with the MATH 140 syllabus.
- Tag claims as evidence, assumption, proposed test or constructed. Never invent citations.
- Keep the transparency log honest about what the tool can't do.

## 🚀 Deploy
- This repo has no Vercel project of its own. To deploy it separately, run `vercel deploy --prod` here. Vercel sends a short-lived OIDC token with each function request; a non-Vercel host needs `AI_GATEWAY_API_KEY`.
- The PDF deliverable is `[TeamName]_M1_CourseMap.pdf`, exported with headless Chrome using `--print-to-pdf`, with the live link on page 1.
