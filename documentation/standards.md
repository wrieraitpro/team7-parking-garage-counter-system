# Team Standards Document

**Project:** Parking Garage Counter System
**Team:** Group 7
**Course:** COP1047C-2265-6452: Introduction to Python Programming

## Team Information

| Team Member            | Role               |
| ---------------------- | ------------------ |
| José Leiva             | Software Developer |
| Julio Mayedo Fernández | Software Developer |
| William Riera          | Project and Documentation Manager, GitHub Coordinator, and Lead Software Developer |

## Coding Standards

- **Naming conventions:** Functions and variables use snake_case (for example, `add_record`, `parking_spaces`). Names are descriptive of their purpose. Constants are written in UPPER_CASE. Status values are stored as the strings `Occupied`, `Available`, and `Reserved`.
- **Indentation:** Four spaces per level of indentation. Tabs are not used (PEP 8).
- **Comments and docstrings:** Every function includes a docstring that states its purpose, parameters, return value, author, and status. Inline comments explain any non-obvious logic. `# TODO` markers identify work deferred to Phase 3.
- **Line length:** Lines are limited to 79 characters, in keeping with PEP 8.

## Git Workflow

- **Branch strategy:** The `main` branch holds stable, reviewed code. Each member works on a feature branch named `feature/<function-name>` (for example, `feature/add-record`).
- **Commit messages:** Messages are written in the present tense and describe a single logical change (for example, `Add add_record() function stub`).
- **Pull requests:** Changes are merged into `main` through a pull request. At least one other member reviews a pull request before it is merged. The GitHub Coordinator resolves any merge conflicts together with the contributing member.

## Team Procedures

- **Communication:** The team communicates through a shared group chat and email. Members are expected to respond within 24 hours.
- **Task assignment:** Tasks are divided so that each member owns at least one function stub. Assignments are recorded in the Team Responsibilities section of the Phase 2 report.
- **Conflict resolution:** Technical disagreements are resolved through team discussion and majority agreement. If a decision cannot be reached, the Project Manager makes the final call. Merge conflicts are handled by the GitHub Coordinator together with the member whose work is affected.
