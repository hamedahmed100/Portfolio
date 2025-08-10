# Quick Deployment Guide for GitHub Pages

## 🚀 Step-by-Step Deployment

### 1. Create GitHub Repository
1. Go to [GitHub.com](https://github.com)
2. Click "New repository"
3. Name it: `your-username.github.io` (for custom domain) or any name
4. Make it public
5. Don't initialize with README (we'll upload files)

### 2. Upload Files
**Option A: Using GitHub Web Interface**
1. Go to your new repository
2. Click "uploading an existing file"
3. Drag and drop all portfolio files:
   - `index.html`
   - `styles.css`
   - `README.md`
   - Any images or assets

**Option B: Using Git Commands**
```bash
# Clone the repository
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name

# Copy all portfolio files to this folder
# Then commit and push
git add .
git commit -m "Add portfolio website"
git push origin main
```

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch
6. Click "Save"

### 4. Your Portfolio is Live!
- If using `your-username.github.io`: `https://your-username.github.io`
- If using custom repo name: `https://your-username.github.io/repo-name`

## 📝 Customization Checklist

Before deploying, make sure to update:

- [ ] Your name and title in the hero section
- [ ] About section with your actual experience
- [ ] Skills and proficiency levels
- [ ] Real project links and descriptions
- [ ] Contact information (email, phone, social links)
- [ ] Profile picture
- [ ] GitHub and LinkedIn URLs

## 🔧 Troubleshooting

**Portfolio not showing up?**
- Check if GitHub Pages is enabled in repository settings
- Wait 5-10 minutes for deployment
- Check the Actions tab for any build errors

**Styling issues?**
- Make sure all CSS files are uploaded
- Check browser console for missing resources
- Verify CDN links are accessible

**Mobile not working?**
- Test on different devices
- Check responsive breakpoints
- Verify viewport meta tag is present

## 📱 Testing Your Portfolio

Test on:
- [ ] Desktop (Chrome, Firefox, Safari, Edge)
- [ ] Mobile (iOS Safari, Android Chrome)
- [ ] Tablet (iPad, Android tablets)
- [ ] Different screen sizes

## 🎯 Next Steps

After deployment:
1. Share your portfolio URL on LinkedIn
2. Add it to your resume
3. Include it in job applications
4. Keep it updated with new projects
5. Consider adding a custom domain

## 🌐 Custom Domain (Optional)

To use a custom domain:
1. Buy a domain (Namecheap, GoDaddy, etc.)
2. Add CNAME record pointing to `your-username.github.io`
3. Add custom domain in GitHub Pages settings
4. Wait for DNS propagation (up to 24 hours)

---

**Need help?** Check the main README.md file for detailed customization instructions.
