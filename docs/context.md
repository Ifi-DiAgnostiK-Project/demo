# Course Context

## Course Type

Type: improve-existing
Working Title: DiAgnostiK Lehr- und Lernraum

## Course Profile

Terminology:
  sessions-called: Lerneinheit
  lectures-called: Lernmodul

Persona type: coach
Agenda required: optional
Pacing: learner-driven
Assessment defaults: quizzes

## Conventions & Standards

Language: de
Tone: formal
Person: Sie
Accessibility: required

LiaScript conventions:
  - Metadata header required for every file: author, email, version, language, narrator, date, icon, logo, tags, comment, title
  - language: de | narrator: Deutsch Male (default)
  - Custom CSS linked via: `link: ./style.css`
  - Shared macro libraries imported from GitHub (Ifi-DiAgnostiK-Project org)
  - Tags used for trade group categorization (e.g. Tischler, Zahntechniker, Maler)
  - Alt text required on all media elements (accessibility: required)
  - Animation counters reset to 0 after each ## heading
  - Exactly one # heading per file (course/material title)

## Additional Notes

- Project: Multi-trade vocational training platform organized by trade groups (Tischler, Zahntechniker, Maler, Raumausstatter, SHK, Belehrungen, Arbeits- und Gesundheitsschutz, Umfragen, Wissensspeicher, Experimente, Sonstige)
- Publishing: LiaScript Exporter via GitHub Actions → GitHub Pages; project YAML files in `project/` folder define collections per trade group
- Brand colors: Primary #1A2F5E (Marineblau), Accent #C9A84C (Handwerksgold)
- Logo: `assets/img/Logo_234px.png` | Hero image: `assets/img/slogan_hero.jpg`
- No `skeletons/` folder — materials were authored directly; skeletons can be created retrospectively if needed
- File naming: descriptive slugs (not `{n}-{type}.md` convention); this is intentional for the existing project
- Shared macro repos: Piktogramme, LiaScript_DragAndDrop_Template, LiaScript_ImageQuiz, Bildersammlung, Tapetensymbole, Textilpflegesymbole
