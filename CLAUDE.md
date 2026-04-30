# CLAUDE.md

## Project Goal
Build a responsive SaaS web app that works well on desktop and mobile.

## Product Direction
- Focus on small, useful workflows.
- Prefer boring, reliable features over flashy complexity.
- Optimize for learning, clarity, and fast iteration.

## Tech Stack
- Next.js
- TypeScript
- Tailwind CSS
- shadcn/ui
- Supabase
- Playwright for E2E tests when needed

## Working Rules
- For any non-trivial task, start with a plan.
- Keep changes small and reversible.
- Do not refactor unrelated code.
- Prefer simple solutions over clever ones.
- If something seems broken, stop and diagnose before adding more code.
- Always verify changes before claiming completion.

## Default Workflow
1. Restate the task briefly.
2. Make a short plan.
3. Implement one slice at a time.
4. Run or describe verification.
5. Summarize what changed and what still needs work.

## Code Quality Rules
- Use TypeScript types where useful.
- Keep components small and reusable.
- Do not introduce unnecessary abstractions.
- Avoid duplicate logic.
- Keep UI responsive by default.

## File and Folder Expectations
- `src/app/` for routes and pages
- `src/components/` for reusable UI
- `src/lib/` for helpers and shared logic
- `src/features/` for domain-specific modules
- `docs/` for product and architecture notes
- `tasks/` for todo lists, decisions, and lessons

## Verification
Before finishing any meaningful change:
- Check the affected files
- Confirm the UI behavior or logic path
- Mention how to test it manually
- Add or update tests when practical

## Communication Style
- Be direct.
- Call out uncertainty.
- Explain trade-offs briefly.
- Prefer actionable next steps over broad advice.