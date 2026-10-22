# ISAAC survey styles

Shared stylesheet for the ISAAC (Intervention for School Anxiety & Absenteeism in Children) Qualtrics surveys.

Served by GitHub Pages at **https://sussexpsychologysoftware.github.io/isaac/isaac.css** and loaded by each survey via *Look & feel → Style → External CSS*.

- Changes go live in all surveys within about 10 minutes of a push to `main`.
- Each survey keeps one line in its own *Custom CSS* box: its module accent colour (`:root{--isaac-accent:#…}`).
- If this file is unavailable, the surveys fall back to their native Qualtrics settings (navy, Arial, white, logo).

Please don't edit `isaac.css` here directly. It is generated from the project's master stylesheet by `build.py`.
