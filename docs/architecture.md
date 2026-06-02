<!-- bettergithub:generated-file -->
# Dalili - Your Academic Guide Architecture

The app is organized as a Vite React client with page-level routes, reusable shadcn-style UI components, hooks for academic domain data, and Supabase migrations for persistence. The current polish pass does not change application code; it documents setup, test expectations, and reviewer flow.

## Reviewer Flow

1. Read the root README for the project purpose, setup, usage, and test signal.
2. Inspect the main source locations:
   - `src`
   - `src/pages`
   - `src/components`
   - `src/hooks`
   - `supabase/migrations`
3. Run or manually verify the project using the test plan.
4. Capture any new screenshot or terminal output under `docs/` so the README stays evidence-based.

## Boundaries

- This documentation pass does not alter runtime behavior.
- Secrets, API keys, and local machine paths should stay out of commits.
- Generated binaries and large local outputs should only be committed when they are intentional assignment artifacts.
