# Sprint Planning Exercise

A hands-on exercise for practicing Scrum ceremonies and Git workflows using a dummy restaurant website.

> **This is a read-only reference repository.** Each team must **fork** this repo and work on their own copy. Do not push changes to this repository.

## Quick Start

1. **Fork** this repo to your GitHub account
2. Add team members as collaborators
3. Clone your fork: `git clone <your-fork-url>`
4. Read [`instructions.md`](instructions.md) for the full guide

## What You Will Do

1. Set up a **GitHub Project board** and re-create the issues in your fork
2. Assign **Scrum roles** (Scrum Master, Product Owner, Dev Team)
3. Conduct **Sprint Planning** and document it in [`sprint-ceremonies/sprint-planning.md`](sprint-ceremonies/sprint-planning.md)
4. Work through 9 user stories to customize the website for McDonalds
5. Use **feature branches** and **Pull Requests** for all changes
6. Conduct **Sprint Review** ([`sprint-ceremonies/sprint-review.md`](sprint-ceremonies/sprint-review.md)) and **Sprint Retrospective** ([`sprint-ceremonies/sprint-retrospective.md`](sprint-ceremonies/sprint-retrospective.md))

## Repository Structure

```
├── instructions.md                  # Full sprint instructions and guidelines
├── sprint-ceremonies/
│   ├── sprint-planning.md           # Sprint Planning template
│   ├── sprint-review.md             # Sprint Review template
│   └── sprint-retrospective.md      # Sprint Retrospective template
├── index.html                       # Main website page
├── menu.html                        # Menu page
├── about.html                       # About page
├── contact.html                     # Contact page
├── blog.html                        # Blog page (to be removed per APP-6)
├── products.html                    # Products page
├── review.html                      # Review page
├── style.css                        # Stylesheet
├── script.js                        # JavaScript
└── image/                           # Image assets
```

## User Stories

| ID    | Title |
|-------|-------|
| APP-1 | Change the website logo |
| APP-2 | Rebrand the website |
| APP-3 | Add a Cheeseburger item |
| APP-4 | Fix the Home Page redirect buttons |
| APP-5 | Link the Google maps to Customers HQ |
| APP-6 | Remove the Blog and Online shopping section |
| APP-7 | Remove search functionality |
| APP-8 | Fix Copyright section |
| APP-9 | Configure Social Media buttons |

## Commit Convention

All commits must use the ticket ID prefix:
```
APP-1: Add McDonalds logo
APP-3: Add cheeseburger to menu section
```

## Reference

- [Reference Task Board](https://github.com/orgs/dcadd26/projects/1) (read-only)
