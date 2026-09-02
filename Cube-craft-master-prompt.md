# MASTER PROMPT — TURN MY LESSON INTO A PAPER-CRAFT CUBE
### RCTF · print-and-build classroom cube · v2

---

## ⚠️ READ THIS FIRST — CHOOSE YOUR ROUTE

**ROUTE A — CODE (default, use this one).**
Ask the AI to output the template as **one self-contained HTML page with an SVG dieline, sized in millimetres**, which you then print to PDF. Only this route can guarantee six exactly equal squares, a crossword grid that closes, and a maze with one continuous solution.

**ROUTE B — IMAGE GENERATION (looks only).**
An image model cannot hold exact geometry, a valid crossword, or a solvable maze — it draws something that *resembles* a cube net. Use Route B only for the artwork, and only with the blank dieline attached as a locked reference. Expect to fix the geometry afterwards.

The prompt below is written for **Route A**. To run it as Route B, delete the FORMAT section and replace it with: *"Output one A3 portrait image. Redraw the attached blank dieline exactly; place artwork only inside the six faces; never redraw or move the outline."*

---

## FILL THIS IN BEFORE SENDING

| Field | Your value |
|---|---|
| Lesson / unit | `………` |
| Subject | `………` |
| Learner age + grade | `………` |
| CEFR band | `………` |
| Language of the cube | `………` |
| Page size | `A3 portrait` (or A4 portrait) |
| Attached: lesson material | `………` |
| Attached: my avatar (PNG) | `………` |
| Attached: my logo (PNG) | `………` |
| Attached: blank cube dieline | `………` |

---

## R — ROLE

You are three specialists working in this order of authority:

1. **A paper-engineer / dieline designer** — you own the geometry, and your decisions override everyone else's.
2. **An instructional designer** — you own what is taught, levelled to CEFR and the DOK ladder.
3. **A children's educational illustrator** — you own how it looks, and you get whatever space the first two leave you.

When these three conflict, the earlier one wins. A beautiful cube that will not fold is a failed deliverable.

---

## C — CONTEXT

The output is a **physical classroom object**, not a poster. A teacher will print it on one sheet, cut one continuous outline, fold, glue seven tabs, and hand a finished cube to a child who will roll it, write on it and drop it.

That reality sets three constraints you must design against:

- **Print, not screen.** Anything under 9 pt disappears; anything under 0.4 pt stroke disappears; pale grey on white disappears on a school photocopier.
- **Folding destroys anything on a fold line.** Content near an edge gets creased, glued over, or cut off.
- **Children write on it.** Answer areas must be white and large enough for a pencil.

The uploaded lesson is the **only source of academic truth**. You may write new questions, clues, puzzle words and prompts, but every one must be answerable from the uploaded material. Invent no facts.

---

## T — TASK

Work in the five stages below **in this order**. Do not begin Stage 3 until Stages 1 and 2 are settled.

### STAGE 1 — BUILD THE GEOMETRY (before any content)

**Net layout — Latin cross, locked:**

```
              ┌────────┐
              │ FACE 1 │           column of four = the band
              ├────────┤             that wraps the cube
    ┌────────┐│ FACE 2 │┌────────┐
    │ FACE 3 ││        ││ FACE 4 │  row of three
    └────────┘├────────┤└────────┘
              │ FACE 5 │
              ├────────┤
              │ FACE 6 │
              └────────┘
```

**Exact measurements — A3 portrait (297 × 420 mm):**

| Item | Value |
|---|---|
| Face side `S` | **80 mm**, all six faces, width = height |
| Glue-tab depth | **10 mm** |
| Net footprint | 3S + 2 tabs = **260 mm** wide × 4S + 1 tab = **330 mm** tall |
| Page margins | 18.5 mm left/right, 45 mm top/bottom (net centred) |

**A4 portrait (210 × 297 mm) alternative:** `S` = 55 mm, tab = 7 mm, footprint 179 × 227 mm, margins 15.5 / 35 mm.

**Alignment:** Faces 1, 2, 5, 6 share one vertical centre line. Faces 3 and 4 share Face 2's horizontal centre line. Every shared edge is exactly `S` long and meets edge-to-edge with no gap and no overlap.

**Glue tabs — exactly seven, no more, no fewer:**

| # | Tab position |
|---|---|
| 1 | FACE 1 — top edge |
| 2 | FACE 1 — left edge |
| 3 | FACE 1 — right edge |
| 4 | FACE 3 — outer left edge |
| 5 | FACE 4 — outer right edge |
| 6 | FACE 5 — left edge |
| 7 | FACE 5 — right edge |

**FACE 2 gets no tabs. FACE 6 gets no tabs.**

*Why seven:* a cube has 12 edges; this net already joins 5 of them as folds, so exactly 7 must be glued, and each glued seam needs one tab.

Tabs are trapezoids with 45° clipped corners, sitting **outside** the square. A tab is never counted in the face measurement. Tabs stay **blank and white** — no text, artwork, logo or grid may enter one.

**Line system — two styles, nothing else:**

- **CUT:** solid, 0.35 mm (1 pt), 100% black, tracing the outer silhouette of the whole piece including tab edges. One continuous closed path — the teacher makes one cut.
- **FOLD:** dashed, 0.18 mm, 40% grey, 3 mm dash / 2 mm gap, on the 5 face-to-face edges and the 7 tab hinges. Nothing else on the page may be dashed.

**Safe zone:** keep all text, grid cells, maze walls, answer boxes, the logo and the avatar's face **6 mm inside every face edge** (8 mm on an edge that carries a tab). Background colour may run to the fold line but never across it.

**Face orientation:** print Faces 1, 2, 3, 4 and 5 upright, and **rotate FACE 6 by 180°**. Face 6 folds up the back of the cube; printed upright it reads upside-down on the finished cube. This single rotation is the difference between a professional template and an amateur one.

### STAGE 2 — MINE THE LESSON

Read the uploaded material and extract, silently: title, unit, main idea, learning objectives, key vocabulary with definitions, characters or key figures, setting, sequence of events or steps, target grammar or skill, and the two or three comprehension points that matter most.

Then decide the levelling and **state it in your report**:

| Face | Activity | DOK | Purpose |
|---|---|---|---|
| 1 | Cover / hook | — | Identify the lesson, invite the child in |
| 2 | Snakes & Ladders | 1–2 | Recall + apply, under playful pressure |
| 3 | Maze | 1 | Sequence or match, low load |
| 4 | Treasure hunt | 2 | Infer, then combine into one answer |
| 5 | Crossword | 1–2 | Vocabulary retrieval and spelling |
| 6 | Exit ticket + self-rating | 3 | Explain, then judge own learning |

Never reassign these six activities to different faces.

### STAGE 3 — BUILD THE SIX FACES INSIDE THE SQUARE

**The rule that governs every face: the content fits the square; the square never resizes for the content.** If it is crowded, cut words, cut questions, use an icon — never enlarge the face.

**Legibility budget at `S` = 80 mm** (scale down proportionally for A4):

| Element | Minimum |
|---|---|
| Body text | 9 pt · **12 pt for ages 6–8** |
| Face title | 18–24 pt, three words maximum |
| Crossword cell | 9 mm → grid no larger than **6 × 6** |
| Snakes & Ladders cell | 16 mm → **16 spaces (4×4)** or 25 (5×5) maximum |
| Maze corridor | 5 mm → maze grid no finer than **9 × 9** |
| Writing line spacing | 8 mm |
| Answer box | 8 × 8 mm per letter |

**FACE 1 — COVER.** Uploaded logo, uploaded avatar in a pose that fits the lesson, the lesson title, the unit, and a four-word hook (*Read. Think. Play. Discover!*). Nothing else. This face should feel uncrowded.

**FACE 2 — SNAKES & LADDERS.** A real board: numbered squares in a boustrophedon path, START, FINISH, at least 2 ladders and 2 snakes drawn between real square numbers, a dice icon. Every square carries either a one-line lesson question or a move instruction. **List the ladder and snake routes explicitly in your report** (e.g. ladder 3→9) so they can be checked.

**FACE 3 — MAZE.** One entrance marked START, one exit marked FINISH, solid walls, and exactly one continuous solvable path between them. Frame the mission in lesson language. Artwork must not sit on the corridors.

**FACE 4 — TREASURE HUNT.** Four to six one-line clues from the lesson. Each clue yields one letter; the letters spell one **secret word taken from the lesson vocabulary**. Number the answer boxes so the child knows the order. State the secret word in your report.

**FACE 5 — CROSSWORD.** A real interlocking grid, 5–6 words, all from the lesson. Numbered start cells, ACROSS and DOWN clue lists beneath the grid, black or omitted cells where there is no letter. Every crossing letter must actually match.

**FACE 6 — EXIT TICKET + HOW DID I DO?** Split the square into two stacked halves. Top: three short prompts with ruled writing space, at least one beginning *Why* or *How*. Bottom: four self-rating statements in the child's voice, each with a five-star or five-circle scale. Remember this face is rotated 180°.

### STAGE 4 — BRANDING

Use **only** the uploaded logo and **only** the uploaded avatar. Do not invent, substitute, recreate from memory, or add any second logo, academy mark or mascot. Preserve the avatar's face, hair, glasses, clothing, proportions and colours; you may change only pose, expression, gesture and the prop being held. Draw the palette from the uploaded logo.

### STAGE 5 — PRINT HYGIENE

- Keep average ink coverage on any face at or below 30%, and keep every answer box, writing line and crossword cell **pure white**.
- The template must survive black-and-white photocopying: test every colour pairing for contrast in greyscale.
- Print a **40 mm reference ruler bar** in the page margin outside the cut line, labelled `40 mm — if this does not measure 40 mm, reprint at 100%`.
- Put a one-line instruction in the margin: **Print at 100% / Actual Size — never "Fit to page".**
- A tiny legend in the margin: `——— cut · – – – fold · ▭ glue tab`.
- No poster furniture: no large instruction panels, no decorative sidebars, no unrelated characters. The net is the page.

---

## F — FORMAT (deliverables)

Produce three things, in this order:

**1. A measurement report — before you render anything.** Print it as a plain list so I can check it:

```
Page size:            A3 portrait, 297 × 420 mm
Face side:            80 mm × 80 mm  (all six identical)
Tab depth:            10 mm
Net footprint:        260 × 330 mm
Margins:              18.5 mm sides, 45 mm top/bottom
Glue tabs:            7   (F1 top/left/right · F3 outer-left · F4 outer-right · F5 left/right)
Fold lines:           5 face-to-face + 7 tab hinges
Face 6 rotation:      180°
CEFR band:            …
DOK per face:         1:— 2:… 3:… 4:… 5:… 6:…
Snakes & ladders:     ladders … → … ; snakes … → …
Crossword words:      … (grid … × …)
Treasure secret word: …
```

**2. The printable template** — one self-contained HTML file with `@page { size: A3 portrait; margin: 0 }`, all geometry drawn as inline SVG in millimetre units, all CSS and images inline, no external links, nothing that depends on the internet. It must print correctly straight from the browser.

**3. A separate answer key** — maze solution, crossword solution, secret word, and suggested answers for the board questions. The key never appears on the cube.

---

## FINAL CHECK — fix any failure before you deliver

```
□ Page is PORTRAIT
□ Six faces exist; every one measures exactly S × S
□ No face is a rectangle, stretched, or shifted off its centre line
□ Layout matches the Latin cross exactly
□ Exactly 7 glue tabs, in the 7 listed positions
□ Face 2 and Face 6 carry no tabs
□ Tabs are outside the squares and change no face dimension
□ Tabs are blank
□ One continuous cut path; the whole craft lifts off the page in one piece
□ Cut solid, fold dashed, nothing else dashed
□ Nothing important within 6 mm of a fold
□ Face 6 is rotated 180°
□ Body text ≥ 9 pt (≥ 12 pt for ages 6–8)
□ Maze has exactly one continuous solution
□ Crossword crossings all match; every answer is in the lesson
□ Secret word is spellable from the clue letters
□ Board has real ladders and real snakes between real numbers
□ Only the uploaded logo; only the uploaded avatar
□ Ruler bar and "print at 100%" note are present
□ Answer key is a separate file
```

**Order of priority, always: geometry → function → learning → decoration. Never trade the first for the last.**
