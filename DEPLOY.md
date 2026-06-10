# Deploy: Headline Title

## Option A - fastest (no git, ~2 min)
1. Unzip this folder anywhere on your Mac
2. Terminal:
   cd headline-title
   npx vercel --prod
3. Log in via browser when prompted, accept defaults. URL prints at the end.

## Option B - git pipeline (for ongoing updates)
1. github.com -> New repository -> "headline-title" (private)
2. "Upload files" -> drop index.html and vercel.json -> Commit
3. vercel.com -> Add New Project -> Import "headline-title" -> Deploy
4. Future updates: replace index.html on GitHub, Vercel redeploys automatically.
