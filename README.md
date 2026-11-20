# AI-Assisted Development Workflows

Repeatable workflows for using Claude and IBM Bob in day-to-day development. Feel free to use and improve these.

---

## Workflow 1: Understanding Unfamiliar Code with IBM Bob's Code Teacher Mode

**When to use:** Onboarding to a new codebase, reviewing code you didn't write, or debugging an unfamiliar area.

**Steps:**
1. Open the file or class in IBM Bob and switch to code teacher mode.
2. Ask for a high-level explanation of what the code does and how it fits into the project.
3. Drill into specific methods, patterns, or concepts you don't understand.
4. When debugging, describe the bug and ask Bob to walk through the likely code path.
5. Verify explanations against the actual code and tests before acting on them.

**Tips:**
- Ask *why* code is written a certain way, not just *what* it does.
- Great for interns and new hires getting up to speed.

---

## Workflow 2: Finding Gaps and Creating GitHub Issues with Claude and IBM Bob

**When to use:** Planning work on a project, finding unimplemented features, or organizing a backlog.

**Steps:**
1. Give Claude or IBM Bob the relevant code (e.g., a class or package from the JDBC client).
2. Ask it to identify unimplemented methods, missing functionality, bugs, or possible enhancements.
3. Review the findings and discard anything inaccurate or out of scope.
4. Ask it to draft each item as a GitHub issue with a clear title, description, technical requirements, and acceptance criteria.
5. Edit the drafts as needed and create the issues in the repo so teammates can pick them up.

**Tips:**
- Work one area at a time for more accurate results.
- Always verify findings against the code; AI can miss context or suggest things that already exist.

---
