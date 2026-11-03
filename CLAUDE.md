# CLAUDE.md — EraseDrop Project Context

## Project Summary
- **App Name:** EraseDrop
- **Description:** 100% In-Browser AI Background Remover (WebGPU/WASM, Zero Server Upload, Batch ZIP, Studio Editor, Pas Foto Presets, IndexedDB History).
- **Owner:** Andreas Restuawanta Christwara ([@zzdevxx](https://github.com/zzdevxx))
- **GitHub:** https://github.com/zzdevxx/erase-drop
- **Live URL:** https://erase-drop.vercel.app

## Tech Stack
- React 18, Vite 8, TypeScript (Strict)
- Tailwind CSS v4 (`@tailwindcss/vite` plugin, `@theme` in `src/index.css`)
- `@imgly/background-removal` (ONNX Runtime Web, WebGPU + WASM SIMD fallback)
- `JSZip` + `file-saver` (Batch download)
- IndexedDB (`erasedrop_db`) for offline history

## Common Workflows
```bash
npm run dev        # Start dev server (http://localhost:5173)
npm run build      # Build for production
npx vercel --prod  # Deploy to Vercel production
git push origin main
```

## Key Documentation
- `PRD.md` — Complete Product Requirements & Features Breakdown
- `DESIGN.md` — Design System Tokens & Guidelines
- `README.md` — User-facing documentation (Bahasa Indonesia)

## Environment Status
- GitHub CLI (`gh`): Logged in as `zzdevxx`
- Vercel CLI: Logged in as `zzdevxx` (Token in user env `VERCEL_TOKEN`)
- Supabase CLI: Configured with 2 active projects
