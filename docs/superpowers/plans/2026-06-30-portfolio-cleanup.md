# Portfolio Cleanup Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Replace the al-folio sample content with a focused static portfolio for Hyunsoo Lee.

**Architecture:** Keep GitHub Pages static hosting. Replace public entry pages with plain HTML/CSS generated from career materials, and update search-index files to avoid broken/sample URLs.

**Tech Stack:** Static HTML, CSS, GitHub Pages, existing image assets.

---

### Task 1: Create rollback point

**Files:**
- Git branch: `codex/portfolio-cleanup`
- Git tag: `codex-before-portfolio-cleanup-20260630`

- [x] Create a feature branch.
- [x] Create a tag on the original HEAD for quick rollback.

### Task 2: Replace public pages

**Files:**
- Modify: `index.html`
- Modify: `projects/index.html`
- Modify: `cv/index.html`
- Modify: `404.html`
- Create: `assets/css/portfolio.css`

- [x] Replace al-folio sample biography and project content with career-based portfolio content.
- [x] Remove navigation to missing `people` and `books` pages.
- [x] Avoid publishing phone number and home address.

### Task 3: Fix indexing and domain metadata

**Files:**
- Modify: `robots.txt`
- Modify: `sitemap.xml`
- Modify: `feed.xml`

- [x] Use `https://githubpage.ithans.com` consistently.
- [x] Include only live public pages in sitemap.

### Task 4: Verify

**Files:**
- Check all edited HTML and CSS.

- [ ] Run grep checks for sample content.
- [ ] Run internal-link checks for public pages.
- [ ] Inspect git diff before reporting results.
