# Git-Flows  
**Weight:** 1  
**Project Duration:**  
- **Start:** Dec 1, 2025, 12:00 AM  
- **End:** Dec 8, 2025, 12:00 AM  

> **Note:** This project requires a Manual QA review. Request it once you are done.

---

## Overview  
Git-Flow is a branching model for Git, proposed by Vincent Driessen, that helps developers manage features, releases, and hotfixes in a structured and scalable way. It introduces organized branch roles and improves collaboration across large teams.

Git-Flow includes:

- **main (or master)** – Production-ready code  
- **develop** – Staging area for features  
- **feature/*** – New features  
- **release/*** – Code preparing for deployment  
- **hotfix/*** – Emergency fixes on main  

---

## Relevance in the Development Process  
Git-Flow improves:

- Code organization  
- Team collaboration  
- Code stability  
- Release management  
- CI/CD integration  

---

## Learning Objectives  
- Understand Git-Flow structure  
- Identify branch roles  
- Apply Git-Flow in real projects  
- Manage feature, release, and hotfix cycles  

---

## Learning Outcomes  
- Explain Git-Flow and its benefits  
- Create and manage Git-Flow branches  
- Use Git-Flow commands  
- Integrate Git-Flow into CI/CD  

---

## Git-Flow Best Practices  

| Best Practice | Description |
|---------------|-------------|
| Start with develop | Always branch off develop, not main |
| Isolate features | Each feature gets its own branch |
| Use Pull Requests | For code review and controlled merging |
| Keep main clean | Only tested production code |
| Tag releases | Tag versions on main |
| Use hotfix/* | For urgent production fixes |
| Document workflow | Keep project workflow documented |

---

## Common Git-Flow Commands

```bash
git flow init
git flow feature start <name>
git flow feature finish <name>
git flow release start <x.x.x>
git flow release finish <x.x.x>
git flow hotfix start <x.x.x>
git flow hotfix finish <x.x.x>
