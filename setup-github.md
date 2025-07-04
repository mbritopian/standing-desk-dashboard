# GitHub Setup Instructions

## Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `standing-desk-dashboard`
3. Make it Public
4. Don't initialize with README (we already have one)
5. Click "Create repository"

## Step 2: Push Your Code
Once you create the repository, GitHub will show you commands. Use these:

```bash
git remote add origin https://github.com/YOUR_USERNAME/standing-desk-dashboard.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

## Step 3: Deploy to Vercel
1. Go to https://vercel.com
2. Sign in with GitHub
3. Click "New Project"
4. Import your `standing-desk-dashboard` repository
5. Deploy!

Your dashboard will be live at a Vercel URL. 