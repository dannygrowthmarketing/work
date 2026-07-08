# Here to Scale — Selected Work

Portfolio hub linking all live GitHub Pages projects: monthly performance reports,
case studies, and the interactive resume. Pure HTML/CSS/JS — one self-contained file,
no build step, no dependencies.

**Live:** `https://dannygrowthmarketing.github.io/work/`

## Features
- Animated canvas constellation hero (vanilla JS)
- Count-up stats on scroll (IntersectionObserver)
- Filterable project cards (Reports / Case Studies / Portfolio)
- 3D hover tilt on cards
- Mobile-first, zero horizontal overflow

## Before pushing — verify two URLs
Open `index.html`, find the `PROJECTS` array (top of the `<script>`), and confirm
the two entries marked `// verify:true`:
- Foremost PA case study slug
- Resume slug

The June report URL is confirmed live. To add July later, copy a project object
and edit — everything renders from the config.

## Deploy
1. Create repo `work`
2. Push these files to `main`
3. Settings → Pages → Deploy from a branch → `main` / root → Save
