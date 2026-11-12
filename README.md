# EDE477 — Mathematics Experience Reflection

**November 10, 2026 | EDU486 Invisible Invaders**

This repository contains the original pre-reading mathematics reflection, now with the **illustrated cover page and three privacy-cropped camp images**. The reflection itself occupies **two pages**; the separate cover is front matter.

## Build in Overleaf

1. Sync/pull the latest GitHub revision into the connected Overleaf project.
2. Keep the existing selected **`response-only.tex`** entry point, or select **`main.tex`**; both now compile the illustrated journal.
3. Compile with **pdfLaTeX**. The output is **one cover + two reflection pages** (3 PDF pages total).

For a version without the cover, compile **`text-only.tex`** (2 PDF pages). The original body-only source was copied there verbatim; `response-only.tex` is now a compatibility entry point for the existing Overleaf main-file setting.

## Main-file compatibility and GitHub synchronization

**Observed November 12:** The live Overleaf project was compiling `response-only.tex`, showing only two body pages. Therefore the source of this repository now makes **`response-only.tex` forward to `main.tex`**, so the existing Overleaf main-file setting produces the illustrated cover and the two-page reflection *after the repository changes are synchronized into Overleaf*.

- Compile `response-only.tex` **or** `main.tex` for **three PDF pages total**: one illustrated cover plus two reflection pages. The cover is front matter, not part of the 1-2 page reflection.
- Compile `text-only.tex` for the original body-only two-page PDF. This is the exact prior `response-only.tex`, preserved byte-for-byte.
- The original `preamble.tex`, `reflection.tex`, `main.tex`, and three cropped images are unchanged. No assigned mathematics readings were inserted.
- **Overleaf GitHub integration may require a pull/sync** from the project Integrations menu before it sees new GitHub commits; GitHub commits alone are not proof the Overleaf cloud project has updated.
- The connected Blackboard submission is separate; **no Blackboard upload or submission was performed**.

## Content and evidence

- **Primary teaching experience:** EDU486 `Invisible Invaders` camp — Field Friday sampling/counting, Litter Meter measuring-wheel corrections, and interpretation of the rough 51 / 405 observations-per-meter calculation.
- **Supporting connection:** the proposed, not yet taught, mathematics extension of the TeachingPlacement marketing/PEST planning task.
- **Reflection questions:** what doing math means; what teaching math looks like; personal experiences as a math learner; and an initial reaction to long-term substituting in a math classroom.
- **Pre-reading boundary:** no assigned November 10 mathematics readings were used to prepare the original reflective draft. Nothing was rewritten for this repository update.

The cover images are selected, cropped visuals from the camp's prior recap materials, not raw proof of a scientific result. They exclude faces and names. **This GitHub repository is public:** do not add uncropped student images, student information, or private placement records.

## Source of truth and status

The detailed source-provenance record, original PDFs, and full Overleaf ZIP remain in the restricted EDE477 course archive. The original three imported source files were preserved. This commit adds the missing cover entry point and assets, with no history rewrite.

**Status: draft for owner review; Blackboard submission not verified.** Editing this repository does not confirm an update to a separate Overleaf project.
