# How to Get This Live on GitHub Pages

I'll walk you through it. Takes like 10 minutes.

## What You Need

- GitHub account (free)
- Git installed ([get it here](https://git-scm.com/))
- A terminal (Command Prompt, PowerShell, or whatever)

## Step 1: Create a Repo on GitHub

1. Go to [github.com](https://github.com)
2. Hit the **+** in the top right corner
3. Click **New repository**
4. Name it: `portfolio`
5. Description: "My portfolio" or whatever
6. Make it **Public**
7. Click **Create repository**

Done. You now have a GitHub repo.

## Step 2: Get Git Ready Locally

Open your terminal and go to your project folder:

```bash
cd e:\MYPORTFOLIOSITE
```

Initialize git:

```bash
git init
git add .
git commit -m "first commit"
```

## Step 3: Connect to GitHub

GitHub will show you a bunch of commands to run. They'll look like:

```bash
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git branch -M main
git push -u origin main
```

Copy those from your GitHub page and run them. Replace `YOUR-USERNAME` with your actual username.

## Step 4: Turn on GitHub Pages

1. Go to your repo on GitHub
2. Click **Settings**
3. Find **Pages** on the left side
4. Under "Build and deployment":
   - Source: Pick "Deploy from a branch"
   - Branch: Select `main` and `/root`
5. Click **Save**

GitHub will deploy it automatically. Takes a minute or two.

## Step 5: Your Site is Live

Check it at:
```
https://YOUR-USERNAME.github.io/portfolio
```

May take a minute. If it's not showing up, wait another minute and refresh.

## Optional: Use Your Own Domain

Want `sisam.dev` instead of `yourusername.github.io/portfolio`?

1. Buy a domain (GoDaddy, Namecheap, whatever)
2. Go to your repo Settings → Pages
3. Type your domain under "Custom domain"
4. Update your domain's DNS settings (registrar will have instructions)

Boom. Now you have a custom domain.

## Troubleshooting

**Site not showing up after 5 minutes?**
- Check the **Actions** tab to see if the build passed
- Make sure you enabled GitHub Pages
- Try refreshing in incognito mode

**Old version still showing?**
- Clear your browser cache
- Try incognito mode
- Wait another minute

**Build failed?**
- Check the Actions tab for errors
- Make sure your default branch is `main` or `master`
- Make sure `.github/workflows/deploy.yml` exists

## 📊 Monitoring Deployments

1. Go to your repository
2. Click **Actions** tab
3. View deployment history and logs
4. Click on any workflow to see details

## Best Practices (Kinda)

✅ **Do:**
- Commit often with good messages
- Update your portfolio regularly
- Don't hardcode sensitive stuff (passwords, API keys)
- Use branches if you're making big changes

❌ **Don't:**
- Commit your API keys or credentials
- Delete the `.github/workflows` folder
- Edit files directly in GitHub's web UI (unless you're lazy, which is valid)

## Next Steps

1. Share your portfolio with people
2. Update it when you do new projects
3. Maybe add Google Analytics if you care about that
4. Make it pretty by filling in all your actual info
5. Update social links to your real LinkedIn/GitHub

## Resources

- [GitHub Pages Docs](https://pages.github.com/)
- [Git Docs](https://git-scm.com/doc)
- [Markdown Cheatsheet](https://www.markdownguide.org/)

---

That's it. You're deployed.
