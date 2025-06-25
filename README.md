# 📂 `.github` (Org-Wide Meta Repository)

> **What is this repo?**  
> This repository holds _shared configuration_ that GitHub automatically applies to **every repository in the My Metric Health organization**.  
> It contains no application code—just templates and automation that keep our workflows consistent.

---

## ✨ What lives here?

| Path | Purpose |
|------|---------|
| `.github/PULL_REQUEST_TEMPLATE.md` or `PULL_REQUEST_TEMPLATE/*.md` | Default pull-request description(s) that appear whenever a contributor opens a PR. |
| `.github/ISSUE_TEMPLATE/` | Reusable issue templates—bug, feature request, tech-debt, etc. |
| `.github/CODEOWNERS` | File-pattern → reviewer mappings; enforces automatic reviewer assignment. |
| `.github/workflows/` | Reusable GitHub Actions workflows that any repo can call with `uses: MyMetricHealth/.github/.github/workflows/<file>@main`. |
| `.github/README.md` (this file) | Explains why this repo exists and how to use it. |

> **Note:** Any individual project repo can override these defaults by adding its own templates or workflows inside its local `.github/` folder.

---

