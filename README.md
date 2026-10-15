# Quiz Hub

Static site: `index.html` (home), `dbms-quiz.html`, `java-quiz.html`.

## Deploy GitHub Pages

```bash
git init -b main
git add .
git commit -m "Add quiz site"
git remote add origin https://github.com/<username>/<repo>.git
git push -u origin main
```

Repo Settings -> Pages -> Source: Deploy from a branch -> Branch: `main` / `/ (root)`.
URL: `https://<username>.github.io/<repo>/`
