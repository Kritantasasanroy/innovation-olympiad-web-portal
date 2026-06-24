# Innovation Olympiad Web Portal

This folder contains the static site for the Bharat Innovation Olympiad.

Quick notes:
- The primary file is `Bharat Innovation Olympiad.dc.html` (served as the site entry).
- `vercel.json` is present to rewrite requests to the DC file.
- `index.html` was added as a compatibility redirect to the DC file.

Deploy to Vercel (recommended):

1. Push this repository to GitHub.
2. In Vercel, import the GitHub repository and deploy (no build step needed).

Or use the Vercel CLI:

```bash
npm i -g vercel
vercel login
vercel --prod
```

If you want, rename `Bharat Innovation Olympiad.dc.html` to `index.html` instead of redirecting.
