# GitHub Setup Instructions

Follow these steps to get your working GitHub link:

## Step 1: Create a GitHub repository

1. Go to https://github.com/new
2. Repository name: `cfg-pda-visualizer`
3. Set to **Public**
4. Do NOT initialize with README (you already have one)
5. Click **Create repository**

## Step 2: Push the code

Open your terminal in the project folder and run:

```bash
git init
git add .
git commit -m "Initial commit: CFG to PDA Visualizer"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/cfg-pda-visualizer.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages** (left sidebar)
3. Under "Source", select **GitHub Actions**
4. The workflow in `.github/workflows/deploy.yml` will auto-deploy

## Step 4: Get your live link

After the Action completes (about 1-2 minutes), your site will be live at:

```
https://YOUR_USERNAME.github.io/cfg-pda-visualizer/
```

That is your **working GitHub link** to submit! ✅
