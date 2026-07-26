# Data Science Portfolio — Retail Analytics

A minimal, elegant portfolio website for a data scientist working in retail
(sales, marketing, customer behavior). Pure HTML/CSS — no build step, no
dependencies. Open `index.html` in a browser and it just works.

## Structure

```
portfolio/
├── index.html                       # Home: hero, projects, skills, about, contact
├── css/
│   └── style.css                    # All styles (shared by every page)
├── js/                              # (empty — add scripts here if needed)
├── projects/
│   ├── voice-of-customer.html       # Case study 1: VoC / NLP / GenAI
│   ├── customer-segmentation.html   # Case study 2: clustering + marketing playbook
│   └── store-performance.html       # Case study 3: KPI scoring & store ranking
└── README.md
```

## How to edit

1. Open the folder in VS Code (`File → Open Folder`).
2. Search for `✏️ EDIT` comments in `index.html` — replace name, intro, skills,
   about section and contact links with your own.
3. In each project page, adjust numbers, quotes and takeaways to reflect your
   real projects (current figures are realistic placeholders).
4. To preview locally, right-click `index.html` → *Open with Live Server*
   (install the "Live Server" VS Code extension), or simply double-click the file.

## How to add a new project

1. Duplicate one of the files in `projects/`.
2. Add a new `<a class="card">…</a>` block in the Projects section of `index.html`
   pointing to it.

## How to publish (free options)

- **GitHub Pages**: push this folder to a repo → Settings → Pages → deploy from
  branch `main`, root folder. Your site will be at `https://username.github.io/repo`.
- **Netlify / Vercel**: drag & drop the folder in their dashboard. Done.

## Design tokens

- Palette: paper `#FBFAF7`, ink `#14181D`, petrol `#0E5E56` (accent),
  amber/red for warning/negative states.
- Type: Newsreader (display), Instrument Sans (body), IBM Plex Mono (data/labels).
