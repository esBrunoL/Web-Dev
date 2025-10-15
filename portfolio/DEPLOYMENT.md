# GitHub Pages Deployment Guide

## Quick Setup for Your Personal Website

### Step 1: Repository Setup
1. Make sure your repository is named `Web-Dev` (or any name you prefer)
2. Ensure all your HTML files are in the root directory
3. Make sure you have an `index.html` file (already created for you)

### Step 2: Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section in the left sidebar
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### Step 3: Access Your Website
Your website will be available at:
```
https://esBrunoL.github.io/Web-Dev/
```

The `index.html` file will automatically redirect visitors to your main page (`Lab1.html`).

### Step 4: Update LinkedIn Profile
Don't forget to update your LinkedIn profile with your GitHub Pages URL:
1. Go to LinkedIn
2. Edit your profile
3. Add your website URL in the contact information section
4. Update the link in your `Lab1.html` file to point to your actual LinkedIn profile

### Step 5: Custom Domain (Optional)
If you want to use a custom domain:
1. Add a `CNAME` file to your repository root
2. Put your domain name in the file (e.g., `brunolobo.dev`)
3. Configure your domain's DNS settings to point to GitHub Pages

### Important Notes:
- It may take a few minutes for your site to be available after enabling Pages
- Any changes you push to the main branch will automatically update your live site
- Make sure all file paths are relative (no absolute paths like `C:\Users\...`)

### Your Website Structure:
```
/
├── index.html (landing/redirect page)
├── Lab1.html (main homepage)
├── Studies.forms.html (study signup form)
├── portfolio.html (portfolio showcase)
├── read.me.studies.html (study guidelines)
├── gridstyle.css (main stylesheet)
├── README.md (documentation)
└── other assets (images, videos, etc.)
```

### Next Steps:
1. **Push all changes** to your GitHub repository
2. **Enable GitHub Pages** as described above
3. **Test your website** by visiting the GitHub Pages URL
4. **Update your LinkedIn** profile with the live website link
5. **Share your website** with friends, family, and potential employers!

Your professional website is now ready to impress! 🚀