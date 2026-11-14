THOMSON PORTFOLIO WITH DECAP CMS

WHAT THIS PACKAGE ADDS
- /admin/ dashboard
- Add/edit/delete projects
- Upload profile and project images
- Edit profile, project titles/descriptions, experience, and skills
- Content stored in /content/*.json
- Images stored in /images/uploads
- Vercel deployment remains automatic after every CMS publish

UPLOAD
Replace the repository contents with all files and folders in this package. Keep the folder structure exactly.

IMPORTANT: OAUTH SETUP REQUIRED
Before login works, edit admin/config.yml and replace:
https://REPLACE-WITH-YOUR-OAUTH-SERVICE.vercel.app
with your deployed Decap GitHub OAuth service URL.

The OAuth service needs a GitHub OAuth App and two Vercel environment variables:
OAUTH_GITHUB_CLIENT_ID
OAUTH_GITHUB_CLIENT_SECRET
Never commit the Client Secret to GitHub.

AFTER OAUTH
Open: https://thomson-saragih.vercel.app/admin/
Log in with the GitHub account that has push access to Thomson2805/thomsonportofolio.

SECURITY
Blur confidential production data before uploading project screenshots. Repository is public.
