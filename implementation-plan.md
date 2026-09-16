## `implementation-plan.md` — Epic SCRUM-1 (Epic A — Circulation: Issue/Return/Due Dates)

Project: My Scrum Space (SCRUM)
Repo: https://github.com/VasanthiGadam05/Library_Management
Epic in scope: SCRUM-1 — Epic A — Circulation (Issue/Return/Due Dates)
Stories in scope (approved backlog fetched):
- SCRUM-4 — A1: Manage Members (create/update/view/list)
- SCRUM-5 — A2: Issue a Book to a Member (issue date + due date)
- SCRUM-6 — A3: Return a Book (close loan, mark book available)

---

## 1) Goal & Outcomes
Deliver end-to-end circulation capability for the Library Management system:
- Maintain Members directory (CRUD + list)
- Issue a book to a member with issue date and due date
- Return a book, closing the loan and restoring book availability
- Ensure data integrity so a book cannot be issued if it is unavailable, and returns reconcile state consistently.

---

## 2) Assumptions / Open Questions (to confirm during implementation)
- Repository currently contains (or will contain) entities for Book and persistence layer (DB/repo).