# Lab Reading Club Hub

This repository contains a lightweight static site for organizing an internal lab reading club. It is intended to be hosted on GitHub Pages from the repository root.

Files:
- `index.html` — Landing page with intro, next meeting box, and organizer contact.
- `schedule.html` — 8-week schedule table. Update this file to change papers/presenters.
- `style.css` — Shared minimal styles for the site.
- `notes/week-01.md` … `notes/week-08.md` — Markdown templates for meeting notes.

How to update the schedule
- Edit `schedule.html` and replace the `TBD` entries with the paper title and presenter name for the appropriate week.
- Commit and push to the default branch (usually `main`). The included GitHub Actions workflow will upload and deploy the site to GitHub Pages on push.

How to update notes
- Open the corresponding file in the `notes/` directory (for example `notes/week-03.md`) and add details below the checklist template.
- Commit and push your changes.

Enabling / publishing
- The repository includes a GitHub Actions workflow that deploys the repository root to GitHub Pages on push to the default branch.
- No external frameworks or Jekyll themes are used; the site is plain HTML/CSS.

License
- Use as internal project content. No license is specified by default.
