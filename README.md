# Professional Portfolio (Static) — for `calchang1994-port`

A polished, recruiter‑ready portfolio with **light/dark mode**, accessible navigation, and two featured projects.

## Projects (links wired for your username)
- **Task Manager (MERN)** — Live: https://task-manager-calchang1994.netlify.app • API: https://task-manager-api-g0uk.onrender.com • Code: https://github.com/calchang1994-port/task-manager
- **To‑Do List (React)** — Live: https://calchang1994-port.github.io/todo-react/ • Code: https://github.com/calchang1994-port/todo-react

> **Resume:** Drop `resume.pdf` in the repo root (next to `index.html`) to automatically show the Resume button on the homepage.

---

## Publish at **https://calchang1994-port.github.io/**
GitHub serves user sites from a repo named **`calchang1994-port.github.io`**.

### 1) Create the repo
- GitHub → **New repository** → name it **`calchang1994-port.github.io`** → Public → Create.

### 2) Upload the site files (root)
Unzip into a clean folder, then:

```bash
unzip portfolio-pro-site-calchang1994-port.zip -d site
cd site
git init
git add .
git commit -m "feat: portfolio for calchang1994-port.github.io"
git branch -M main
git remote add origin https://github.com/calchang1994-port/calchang1994-port.github.io.git
git push -u origin main
```

Or via web: open `calchang1994-port.github.io` → **Add file → Upload files** → drag the **contents** of the zip (not the zip itself) → **Commit**.

### 3) Enable Pages (if needed)
Settings → **Pages** → Build and deployment → **Source: Deploy from a branch** → Branch: `main` · Folder: `/ (root)` → **Save**.  
Wait for the **github-pages** deployment (green).

### Optional
- Add your LinkedIn URL inside `index.html` (`#contact` section).
- Replace email with your real one.
- Add `resume.pdf` to enable the Resume button.

---

## Common issues
- **Site not found / 404**: `index.html` isn’t at root, or repo isn’t named `calchang1994-port.github.io` exactly.
- **Old content**: wait ~1–2 min, hard refresh, check **Deployments → github-pages**.
- **Broken links**: update `index.html` project URLs if your repo/site names differ.

© 2025 Calvin Chang
