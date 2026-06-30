# FacilityCheck Project Addition Implementation Plan

> **For agentic workers:** REQUIRED SUB-SKILL: Use superpowers:executing-plans to implement this plan task-by-task. Steps use checkbox (`- [ ]`) syntax for tracking.

**Goal:** Add the March-November 2024 FacilityCheck personal project to the bilingual portfolio project history.

**Architecture:** Keep Korean as the default project page and English under `/en/projects/`. Add one matching project card before the 2026 StockOps personal cloud project so the chronology reads naturally.

**Tech Stack:** Static HTML, existing portfolio CSS, GitHub Pages.

---

### Task 1: Add FacilityCheck Project Cards

**Files:**
- Modify: `/Users/hans/Documents/git_repository/hansLee-it.github.io/projects/index.html`
- Modify: `/Users/hans/Documents/git_repository/hansLee-it.github.io/en/projects/index.html`

- [x] **Step 1: Update project-page lead text**

Korean text now mentions facility-management web work. English text now mentions facility-management web work.

- [x] **Step 2: Insert Korean project card**

The Korean page includes `2024.03 - 2024.11 · Personal Project` and describes FacilityCheck as a Spring Boot facility-management web system.

- [x] **Step 3: Insert English project card**

The English page includes `2024.03 - 2024.11 · Personal Project` and mirrors the Korean content for overseas review.

- [x] **Step 4: Verify**

Run `git diff --check`, search for `FacilityCheck`, and verify `/projects/` plus `/en/projects/` over the local static server.

- [x] **Step 5: Commit**

Commit with `feat: add FacilityCheck project history`.
