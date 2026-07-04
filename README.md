# CSR400 · Soft & Rigid Body — Learning Guide Website

A 6-week learning guide for the CSR400 Soft & Rigid Body course (AEU, Asia e University, Malaysia), adapted for **Blender 4.0+**. Retro 70s poster design, built with plain HTML & CSS — no frameworks, no build step.

**Lecturer:** Mohd Faiz bin Alias

## Files

| File | Use when |
|------|----------|
| `csr400-learning-guide.html` | Hosting online (GitHub Pages, Netlify, university server). Videos play **embedded in the page** — click a thumbnail to load the player. |
| `csr400-learning-guide-offline.html` | Sharing the file directly (email, LMS upload, USB). Clicking a thumbnail opens the video **on YouTube in a new tab**. Works when opened straight from disk. |

> Note: YouTube blocks embedded playback on pages opened via `file://` (Error 153). That's why the offline edition exists. To test the embedded version locally, run `python3 -m http.server` in this folder and open `http://localhost:8000/csr400-learning-guide.html`.

## Content

- Course info: objectives, learning outcomes, synopsis, references
- **6 weekly lessons, 3 YouTube tutorials each (18 total):**
  1. Introduction to Rigid Bodies
  2. Introduction to Constraints
  3. Active & Passive Bodies, Solvers, Baking *(Assignment 1 briefing)*
  4. Introduction to Soft Bodies *(Assignment 1 submission)*
  5. Soft Bodies on Rigged Characters
  6. Shatter Effects & Final Project *(Final assignment briefing)*
- Weekly practice challenges and a "Watch on YouTube" fallback link on every video

## Maintenance

Videos belong to their creators on YouTube and may occasionally be removed. To swap a video, replace its ID (the code after `embed/` or `watch?v=`) in both the thumbnail URL and the link — everything else stays the same. A quick check once per semester is recommended.
