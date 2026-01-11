# Sweet Favor

## Overview
A romantic animated Next.js website with animated text, hearts, and music. The app displays a series of screens with animations and lyrics.

## Tech Stack
- Next.js 16
- React 19
- Tailwind CSS 4
- Framer Motion (animations)

## Project Structure
```
src/
  app/          - Next.js app router (layout, page, globals.css)
  components/   - React components (screens, UI elements)
  lib/          - Utilities
public/
  audio/        - Background music (bg.mp3)
  gifs/         - Animated GIFs
```

## Running the Project
- Development: `npm run dev -- -p 5000 -H 0.0.0.0`
- Build: `npm run build`
- Production: `npm run start -- -p 5000 -H 0.0.0.0`

## Deployment
Configured for autoscale deployment on Replit.
