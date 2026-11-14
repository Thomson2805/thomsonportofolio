FIXED STATIC PORTFOLIO - NO NODE.JS REQUIRED

ROOT CAUSE FIXED
The previous JavaScript contained a line-break syntax error. The scroll-reveal elements stayed at opacity 0, so sections looked empty after navigation. This version fixes the script and adds a fail-safe so content remains visible even if JavaScript is unavailable.

REDEPLOY TO VERCEL
1. Delete the old files in your GitHub repository, or replace them.
2. Upload all three items from this package to the repository root:
   - index.html
   - Thomson_Saragih_CV.pdf
   - vercel.json
3. Commit the changes.
4. Vercel will redeploy automatically.
5. Open the site and press Ctrl+F5 once to clear the old browser cache.

LOCAL TEST
Double-click index.html. Click About, Experience, Skills, Projects, Education, and Contact.
