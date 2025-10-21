This repository demonstrates a small collection of advanced form components and example pages built with Next.js and React.

## What this repo contains

- Example pages (in `src/app`):

  - `page.tsx` — basic demo/home page
  - `page-react-hook-form-basic.tsx` — simple form using react-hook-form
  - `page-react-hook-form-advanced.tsx` — advanced react-hook-form examples
  - `page-tanstack-form-basic.tsx` — simple form using @tanstack/react-form
  - `page-tanstack-form-advanced.tsx` — advanced tanstack form examples

- Reusable components:
  - `src/components/form/` — form building blocks: `FormBase.tsx`, `FormInput.tsx`, `FormSelect.tsx`, `FormCheckbox.tsx`, `FormTextarea.tsx`, `hooks.tsx`.
  - `src/components/ui/` — small UI primitives (input, label, button, textarea, etc.) used by the form components.

The goal is to provide composable, type-safe form components and examples you can copy into your own projects.

## Quick start (local)

Open a terminal in the project root and run (PowerShell / Windows):

```powershell
npm install
npm run dev
```

Then open http://localhost:3000 in your browser.

Notes:

- This project uses Next.js and React (see `package.json` for exact versions).
- If you use CI, prefer `npm ci` to install exactly from the lockfile.

## Recommended workflow

- Keep the lockfile (`package-lock.json`, `yarn.lock` or `pnpm-lock.yaml`) committed to the repo so everyone (and CI) installs the same dependency tree.
- Run `npm install` after pulling changes. If dependencies are out of sync, remove `node_modules` and run `npm install` (or run `npm ci` in CI).

## Contributing

Contributions and bug reports are welcome. Open an issue or submit a PR that includes a short description and a runnable repro if possible.

## License

This project is released under the terms in the `LICENSE` file.
