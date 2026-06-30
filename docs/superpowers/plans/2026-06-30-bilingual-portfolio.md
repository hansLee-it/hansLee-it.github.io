# Bilingual Portfolio Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:subagent-driven-development (recommended) or superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Add an English version of the portfolio while keeping Korean as the default.

**Architecture:** Keep root Korean pages as canonical default pages, add English counterparts under `/en/`, and connect each page pair with visible KO/EN switches and `hreflang` metadata.

**Tech Stack:** Static HTML, CSS, GitHub Pages.

---

### Task 1: Add English page set

**Files:**
- Create: `en/index.html`
- Create: `en/projects/index.html`
- Create: `en/cv/index.html`
- Create: `en/404.html`

- [x] Translate home, projects, and CV content into professional English.
- [x] Keep sensitive phone/address details unpublished.

### Task 2: Add language switching

**Files:**
- Modify: `index.html`
- Modify: `projects/index.html`
- Modify: `cv/index.html`
- Modify: `404.html`
- Modify: `assets/css/portfolio.css`

- [x] Add KO/EN switch links to the header.
- [x] Add `hreflang` alternates for Korean, English, and x-default.

### Task 3: Update indexing

**Files:**
- Modify: `sitemap.xml`
- Modify: `feed.xml`

- [x] Include both Korean and English public pages.
- [x] Keep Korean root as x-default.

### Task 4: Verify

- [ ] Check all six public pages return HTTP 200.
- [ ] Check language switch links point to existing pages.
- [ ] Check desktop/mobile layout has no horizontal overflow.
