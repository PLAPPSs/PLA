# Deploying Pakistan Law App to GitHub Pages

Follow these steps to deploy the Pakistan Law App to your GitHub account:

## 1. Create a New GitHub Repository

1. Go to [GitHub](https://github.com) and log in to your account
2. Click the "+" icon in the top-right corner and select "New repository"
3. Name your repository (e.g., "pakistan-law-app")
4. Make the repository public
5. Click "Create repository"

## 2. Upload the Files

### Option 1: Upload via GitHub Web Interface

1. Navigate to your new repository
2. Click the "Add file" dropdown and select "Upload files"
3. Drag and drop all files from the `docs` folder into the upload area
4. Add a commit message like "Initial upload of Pakistan Law App"
5. Click "Commit changes"

### Option 2: Using Git Command Line

1. Open a terminal/command prompt
2. Navigate to the `docs` directory:
   ```
   cd docs
   ```
3. Initialize a Git repository:
   ```
   git init
   ```
4. Add the files:
   ```
   git add .
   ```
5. Commit the files:
   ```
   git commit -m "Initial commit of Pakistan Law App"
   ```
6. Add your GitHub repository as remote:
   ```
   git remote add origin https://github.com/YOUR_USERNAME/pakistan-law-app.git
   ```
7. Push the files:
   ```
   git push -u origin master
   ```

## 3. Configure GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings"
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch (or "master" if that's what you used)
5. Click "Save"
6. Wait a few minutes for GitHub to build your site

## 4. Access Your Deployed App

Once GitHub Pages has finished deploying, you'll see a message saying:
"Your site is published at https://YOUR_USERNAME.github.io/pakistan-law-app/"

Visit this URL to see your deployed Pakistan Law App!

## 5. Set Up a Custom Domain (Optional)

If you have a custom domain, you can configure it in the GitHub Pages settings.

1. Go to your repository settings
2. In the GitHub Pages section, enter your custom domain
3. Update your domain's DNS settings as instructed by GitHub

## Important Notes

- GitHub Pages may take a few minutes to deploy your site after pushing changes
- Make sure all file paths in your HTML, CSS, and JavaScript files are relative and correct
- If you have issues, check the GitHub Pages documentation or open an issue in this repository

Enjoy your deployed Pakistan Law App!
