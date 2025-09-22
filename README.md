# Ecoregional Models: PNW Regime Shifts Hazards — Starter Website & README Kit

This guide supports Innovation Summit 2025 Group 10 as we use this repository for two linked purposes:

1. A **public-facing website** that shares our progress and findings during the sprint.
2. A **shared code and documentation hub** where teammates collaborate on analyses.

The instructions below keep the original template structure but highlight details specific to our project (repository name, storage links, and GitHub Pages workflow).

**Template users:** If you cloned this from the original template, review [TEMPLATE_GUIDE.md](TEMPLATE_GUIDE.md) for a full checklist of items to customize (names, links, branding, etc.).

---

## 1) Understanding the Repository

Think of this repository as a **shared online workspace**. Key pieces include:

* **README.md** — This file (what you’re reading) explains the structure and setup steps.
* **code/** — Python/R scripts, notebooks, and other runnable pieces you want to share.
* **docs/** — Markdown that powers the public website (`https://cu-esiil.github.io/ecoregional-models-pnw-regime-shifts-hazards-innovation-summit-2025__10/`).
* **documentation/** — Optional space for internal notes, longer briefs, or background material.

### Storage expectations

- **Code (`code/`)** — Keep filenames clear and add a short comment or README so others know how to run each script/notebook.
- **Documentation (`docs/` and `documentation/`)** — `docs/` is the public story; `documentation/` can hold extended notes. Reference major updates on the website so visitors understand current findings.

---

## 2) How to Update the Website

Anything inside `docs/` becomes part of the website. When you change a Markdown file there, the site rebuilds via GitHub Actions.

### Step by step

1. In the repository, open the **docs/** folder.
2. Click `index.md` — this is the homepage.
3. Use the ✏️ **Edit** button (top right) to modify the file directly in your browser.
4. Update text, swap images (see `docs/assets/`), and adjust links to match our project.
5. At the bottom, write a short commit message like `update homepage intro`.
6. Click **Commit changes**.

> The site rebuilds automatically after each commit. Wait a minute, then refresh the public URL to verify your edits.

**Need to enable Pages first?** Make sure GitHub Pages is configured to use the included MkDocs workflow. See the setup section below.

---

## 3) How to Share Code

Put scripts, notebooks, or supporting utilities in the `code/` directory. Organize by topic if helpful (`code/data-prep/`, `code/modeling/`, etc.).

### Step by step

1. In the repository, open the **code/** folder.
2. Choose **Add file → Upload files** (to add from your computer) or **Add file → Create new file**.
3. Name the file clearly (e.g., `hydro_model.py`, `fire-risk.ipynb`).
4. At the top of the file, add a short comment summarizing its purpose or usage.
5. Provide a concise commit message such as `add initial hydro model script`, then **Commit changes**.

Collaborators can now review, run, and iterate on shared code.

---

## 4) Common Tasks

* **Add a new webpage:** Create another `.md` file inside `docs/`. MkDocs will publish it automatically when linked from navigation (`mkdocs.yml`) or the homepage.
* **Add an image:** Upload to `docs/assets/` and embed with standard Markdown syntax: `![caption](assets/filename.png)`.
* **Add team members:** Edit `docs/team.md` (or the **Team** section on `index.md`) with names, roles, and contact details.

---

## 5) Tips for Beginners

* Small, frequent commits are easier to review than large ones.
* Don’t worry about perfection—capturing progress is more important than polish during the sprint.
* Keep large data files out of GitHub. Use the CyVerse group folder and link to the data from the **Data** page.

---

## 6) Learn More

* [GitHub Pages basics](https://docs.github.com/en/pages/getting-started-with-github-pages/about-github-pages)
* [Editing files in your browser](https://docs.github.com/en/repositories/working-with-files/managing-files/editing-files)
* [MkDocs Material documentation](https://squidfunk.github.io/mkdocs-material/)

---

## 7) First Things to Try

1. Edit `docs/index.md` with our project description and an initial visual.
2. Add yourself to the team section so visitors know who’s involved.
3. Upload or link our first analysis notebook in `code/`.
4. Refresh the live site and confirm the updates are visible.

Congratulations—you’re contributing to the Ecoregional Models: PNW Regime Shifts Hazards project!

---

## Beginner mode: from zero to website (no command line)

> This section walks someone new to GitHub through the essentials. Everything can be done in a browser.

### What you need

* A GitHub account (free). Sign up at [https://github.com](https://github.com) if you don’t have one.
* Access to this repository: <https://github.com/CU-ESIIL/ecoregional-models-pnw-regime-shifts-hazards-innovation-summit-2025__10>.

### Step 1 — Join the repository

1. Open the invitation link you received by email or GitHub notification.
2. Click **Accept invitation** so you can edit files.

### Step 2 — Open the project home

1. Visit <https://github.com/CU-ESIIL/ecoregional-models-pnw-regime-shifts-hazards-innovation-summit-2025__10>.
2. Explore folders like `docs/`, `code/`, and files like `README.md`.

### Step 3 — Turn on the website (GitHub Pages via Actions)

1. Click the **Settings** tab of the repository.
2. In the left sidebar, choose **Pages**.
3. Under **Build and deployment → Source**, select **GitHub Actions**.
4. Approve the prompt to allow the workflow if GitHub asks.
5. Trigger the **Deploy site (MkDocs)** workflow from the **Actions** tab (choose the workflow → **Run workflow** → branch `main`).
6. After the job succeeds, the live site appears at <https://cu-esiil.github.io/ecoregional-models-pnw-regime-shifts-hazards-innovation-summit-2025__10/>.

### Step 4 — Edit the homepage

1. Return to the **Code** tab and open `docs/index.md`.
2. Click the **pencil icon** to edit.
3. Update the title, intro paragraph, and hero links to reflect our project.
4. Write a short commit message (e.g., `customize homepage`).
5. Click **Commit changes**.

### Step 5 — Check the live site

1. Visit <https://cu-esiil.github.io/ecoregional-models-pnw-regime-shifts-hazards-innovation-summit-2025__10/>.
2. Refresh after a minute—your edits should appear once the workflow completes.

### Step 6 — Add a new page

1. Inside `docs/`, choose **Add file → Create new file**.
2. Name it something like `methods.md` and paste an outline.
3. Commit the file.
4. To expose it in the top navigation, open `docs/_config.yml`, find `header_pages:`, and add `- methods.md`.

### Step 7 — Add an image

1. Upload a photo or figure to `docs/assets/` (drag-and-drop works).
2. Embed it in Markdown: `![Caption](assets/filename.png)`.
3. Commit the change and refresh the live site.

You now know how to collaborate, publish updates, and keep the Innovation Summit audience informed.
