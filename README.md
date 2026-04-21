# motiveworks-website

MotiveWorks 포트폴리오 웹사이트.

## Stack
- Static HTML (single file: `index.html`)
- React 18 UMD + Tailwind CDN + Framer Motion
- Babel standalone for in-browser JSX

## Local preview
```
python3 -m http.server 8080
# http://localhost:8080
```

## Deploy (Vercel)
```
vercel        # first time
vercel --prod # production
```

## Deploy (GitHub + Vercel)
```
git remote add origin git@github.com:<user>/motiveworks-website.git
git push -u origin main
```
Then import the repo in Vercel for auto-deploy on push.
