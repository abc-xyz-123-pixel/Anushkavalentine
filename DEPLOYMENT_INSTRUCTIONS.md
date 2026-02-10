# Deploy Birthday Wish to Vercel

## ⚡ Quick Deploy Steps:

### Option 1: Drag and Drop (Easiest & Recommended)
1. Go to https://vercel.com
2. Sign in with GitHub, GitLab, or Bitbucket (or create account)
3. Click "Add New..." → "Project"
4. Click "Browse" or drag ALL these files together:
   - index.html
   - vercel.json
   - package.json
5. Click "Deploy"
6. Wait 30-60 seconds
7. Your site will be live with a URL like: `https://your-project.vercel.app`

### Option 2: GitHub Repository (Recommended for updates)
1. Create a new repository on GitHub
2. Upload ALL three files to the repository:
   - index.html
   - vercel.json
   - package.json
3. Go to https://vercel.com
4. Click "Add New..." → "Project"
5. Click "Import Git Repository"
6. Select your GitHub repository
7. Click "Deploy"
8. Done! Your site will auto-update when you push changes

### Option 3: Using Vercel CLI
1. Install Vercel CLI:
   ```bash
   npm i -g vercel
   ```

2. Navigate to the folder containing all files:
   ```bash
   cd /path/to/your/folder
   ```

3. Deploy:
   ```bash
   vercel
   ```

4. Follow the prompts and your site will be deployed!

## 🎯 Important Notes:

- **Make sure to upload ALL files together** (index.html, vercel.json, package.json)
- The vercel.json ensures proper routing
- After deployment, the URL will be: `https://[your-project-name].vercel.app`
- You can customize the domain in Vercel settings

## 🐛 Troubleshooting 404 Errors:

If you see a 404 error:
1. Make sure you uploaded ALL three files (index.html, vercel.json, package.json)
2. In Vercel dashboard, go to your project → Settings → General
3. Check that "Root Directory" is set to `./` (or leave blank)
4. Redeploy from the Deployments tab

## 🎨 What's Included:

- Beautiful gradient background (purple theme)
- Animated confetti, balloons, fireworks, stars
- Interactive candle blowing (5 candles)
- Make a wish feature with text input
- Mega celebration button
- Fully responsive design
- Works on all devices

## 🎉 How to Use:

1. Click each candle to blow it out
2. After all candles are blown, write a wish
3. Submit the wish for an epic fireworks show!
4. Click "Celebrate!" button anytime for more fireworks

Enjoy! 🎊

