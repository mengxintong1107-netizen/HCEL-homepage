# Human-centric Embodied Intelligence Lab Website

This is an English laboratory homepage built from the official
[HugoBlox/kit](https://github.com/HugoBlox/kit) `academic-cv` starter.

## What to Edit

- Site name, description, theme, footer: `config/_default/params.yaml`
- Navigation: `config/_default/menus.yaml`
- Homepage blocks: `content/_index.md`
- PI/lab profile: `data/authors/me.yaml`
- Publications: `content/publications/`
- Projects: `content/projects/`
- News: `content/news/`
- Static files such as PDFs: `static/uploads/`
- Images and avatars: `assets/media/`

## Local Preview

Install Hugo Extended and pnpm, then run:

```powershell
pnpm install
pnpm run dev
```

The development server will print a local URL, usually `http://localhost:1313/`.

## Build

```powershell
pnpm run build
```

The generated static site will be written to `public/`.

## Next Customization Pass

Replace the placeholders:

- `Human-centric Embodied Intelligence Lab`
- `Prof. Your Name`
- `Northwestern Polytechnical University`
- `lab@example.edu`
- sample publications, projects, and news items
- `baseURL` in `config/_default/hugo.yaml`
