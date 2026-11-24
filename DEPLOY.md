# Deploy this portfolio to Vercel

The portfolio is live at **https://anilreddysbs.vercel.app**. The deployed site is a self-contained static website whose entry point is `index.html` in the repository root. It uses plain HTML and CSS: no Node.js app, package installation, build command, API keys or environment variables are required.

The Vercel project is already deployed. The steps below are for importing the repository again or setting up a fresh Vercel project.

## Deploy with the Vercel dashboard

1. Open [Vercel](https://vercel.com/) and sign in with the GitHub account that owns `anilreddysbs/anilreddysbs`.
2. Select **Add New → Project**.
3. Find the `anilreddysbs/anilreddysbs` repository and select **Import**.
4. Configure the project:
   - **Project name:** choose a name such as `anil-portfolio`.
   - **Framework Preset:** `Other`.
   - **Root Directory:** `./` (the repository root).
   - **Build Command:** leave it blank. If Vercel enables the Build Command override, keep it empty so Vercel skips the build step.
   - **Output Directory:** serve the repository root (`.`). With the `Other` preset and no `public` folder, Vercel uses the project root for a no-build static site.
   - **Install Command:** leave it blank.
5. Select **Deploy**.
6. When deployment finishes, open the generated `.vercel.app` URL and check the page, navigation, project links, email link and mobile layout.
7. In the project’s **Settings → Domains**, you can add or change the domain later.

## Automatic updates after deployment

The repository is connected to Vercel through Git integration. Commits pushed to the configured production branch (currently `main`) can trigger new deployments automatically. You can also preview changes before promoting them to production.

## Files used

- `index.html` — the complete responsive portfolio website.
- `README.md` — profile overview and project summary.
- `DEPLOY.md` — these deployment instructions.

No application source files from your other repositories are needed to deploy this portfolio.

## Troubleshooting

- If Vercel detects a framework unexpectedly, select **Other**.
- If the build step fails because it is trying to run a command, clear the Build Command override and redeploy.
- If the generated URL shows a 404, verify that the project Root Directory is the repository root and that `index.html` is at that root.
- You can redeploy from the **Deployments** tab after changing project settings.

## Official Vercel documentation

- [Deploying Git repositories](https://vercel.com/docs/git)
- [Configuring a build and static sites without a build step](https://vercel.com/docs/builds/configure-a-build)
