# Sprint 1 - McDonalds Website Customization

Welcome to our Initial Sprint. The goal of this sprint is to customize a web application for our customer, McDonalds.

> **IMPORTANT**: This is a read-only reference repository. Do NOT push changes here. Each team must fork this repo and work on their own copy.

## Getting Started

### 1. Fork and Clone

1. **One team member** forks this repository to their own GitHub account
2. Add all other team members as **collaborators** (Settings > Collaborators)
3. Each team member clones the fork locally:
   ```bash
   git clone <your-fork-url>
   ```

### 2. Set Up Your Project Board

1. Go to your forked repo on GitHub
2. Click **Projects** > **Link a project** > **New project**
3. Choose **Board** view and name it "Sprint 1"
4. Re-create all 9 user stories as **Issues** in your forked repo (copy the title AND description from the [reference board](https://github.com/orgs/dcadd26/projects/1))
5. Add all issues to your Project board
6. Create a **Milestone** called "Sprint 1" under Issues > Milestones, and assign all issues to it

### 3. Assign Scrum Roles

Decide within your team who takes which role:

- **Scrum Master** (1 person) - Facilitates ceremonies, removes blockers
- **Product Owner** (1 person) - Prioritizes backlog, accepts/rejects work
- **Development Team** (remaining members) - Implements the user stories

### 4. Sprint Workflow

1. **Sprint Planning**: Fill out [sprint-ceremonies/sprint-planning.md](sprint-ceremonies/sprint-planning.md) together as a team
2. **Development**: Work on user stories using feature branches (see branching strategy below)
3. **Sprint Review**: Fill out [sprint-ceremonies/sprint-review.md](sprint-ceremonies/sprint-review.md) and demo completed work
4. **Sprint Retrospective**: Fill out [sprint-ceremonies/sprint-retrospective.md](sprint-ceremonies/sprint-retrospective.md) and agree on improvements

> The original repo and task board are available for reference only:
> - Repository: [dcadd26/sprint-planning](https://github.com/dcadd26/sprint-planning)
> - Task Board: [Sprint Board](https://github.com/orgs/dcadd26/projects/1)

## Branching Strategy

Each user story should be developed on its own branch and merged via Pull Request:

```
main
 └── APP-1/change-logo
 └── APP-2/rebrand-website
 └── APP-4/fix-redirect-buttons
 ...
```

1. Create a branch from `main`: `git checkout -b APP-1/change-logo`
2. Make your changes and commit with the ticket prefix: `git commit -m "APP-1: Add McDonalds logo"`
3. Push and open a **Pull Request** to `main`
4. Another team member reviews and approves the PR
5. Merge the PR and move the issue to **Done** on the project board

## Story Point Estimation

Use the following scale to estimate user stories:

| Points | Meaning |
|--------|---------|
| 1 | Trivial or easy change |
| 2 | Research is required |
| 5 | Requires coordination |
| 8 | Complex task |
| Bugfix | Immediate intervention |

### Planning Poker

Use planning poker to estimate user stories collectively. This enables clarity and transparency within the team, so that two estimation extremes (e.g. 1 and 8) can present their views on the task approach.

Link: [Planning Poker](https://planning-poker-agile.web.app/)

## Definition of Done

The items below should be completed (if applicable) for every ticket before being moved to Done:

- [ ] Change is tested locally
- [ ] PR is reviewed and approved by at least one team member
- [ ] PR is merged to `main`
- [ ] Create follow-up ticket if necessary
- [ ] Provide PR link in the issue comments
- [ ] Provide Ticket ID in commit message (e.g. `APP-1: Fix logo`)

## Friendly Reminders

- Break down User Stories into smaller tasks so they can be estimated and planned easier
- Commit frequently
- Provide status updates frequently on User Story tickets
- Use the `APP-X:` prefix in **all** commit messages
- Update your issue status on the Project board as you work (Todo > In Progress > Done)
