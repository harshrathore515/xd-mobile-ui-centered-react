# XD Mobile UI (React + Vite + Tailwind)

This project centers a **mobile app UI** on the page and provides **smooth navigation** between screens (Home → Onboarding → Login → Dashboard). It’s structured for **pixel-snug** work so you can match an Adobe XD spec by tweaking Tailwind classes and CSS variables.

## Stack
- React 18 + Vite
- Tailwind CSS 3
- React Router 6
- Framer Motion, Lucide Icons

## Local Dev
```bash
npm install
npm run dev
```
Visit http://localhost:5173

## Build
```bash
npm run build
npm run preview
```

## Deploy
- **Vercel**: Import this repo, select the Vite preset. Build Command: `npm run build`, Output: `dist`.
- **Netlify**: Build: `npm run build`, Publish directory: `dist`.

## Pixel-Perfect Tips
- Adjust `--phone-w` and `--phone-h` in `src/styles.css` to your XD frame size for precise matching.
- Use the `inner-pad` utility (20px) and Tailwind spacing to nudge positions to match the spec.
- Replace components in `src/pages` with your actual screen layouts from the XD design.
