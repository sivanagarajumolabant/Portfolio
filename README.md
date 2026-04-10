# Portfolio Website - M. Siva Naga Raju

A modern, responsive portfolio website showcasing professional experience, skills, and projects.

## 📁 Files

- `index.html` - Main portfolio website (single-page application)
- `Resume_Professional.md` - Markdown version of resume
- `README.md` - This deployment guide

---

## 🚀 DEPLOYMENT GUIDE - GitHub Pages (FREE Forever)

### ✅ **Why GitHub Pages?**
- ✅ 100% FREE forever
- ✅ Professional URL: `https://YOUR-USERNAME.github.io/portfolio/`
- ✅ Perfect for LinkedIn sharing
- ✅ Easy to update anytime
- ✅ Owned by Microsoft - reliable and secure
- ✅ No ads, no expiration

---

## 📋 STEP-BY-STEP DEPLOYMENT

### **STEP 1: Create GitHub Account** (Skip if you already have one)

1. Open browser and go to: **https://github.com**
2. Click **"Sign up"** button (top right)
3. Enter your email, create password, choose username
4. Verify your email address
5. Login to GitHub

---

### **STEP 2: Create New Repository**

1. Once logged in, click the **"+"** icon (top right corner)
2. Select **"New repository"**
3. Fill in the details:
   - **Repository name:** `portfolio` (or any name you like)
   - **Description:** "My professional portfolio website"
   - **Make it PUBLIC** ✅ (required for free GitHub Pages)
   - ✅ Check **"Add a README file"**
4. Click **"Create repository"** button

Your repository URL will be: `https://github.com/YOUR-USERNAME/portfolio`

---

### **STEP 3: Upload Your Portfolio File**

**Method A: Using GitHub Website (Easiest)**

1. In your repository page, click **"Add file"** button
2. Select **"Upload files"**
3. Click **"choose your files"** or drag and drop
4. Navigate to:
   ```
   c:\Quadrant-Repos\QMigrator_Modules\Web-Agents\Resume-Preparation\
   ```
5. Select and upload **`index.html`**
6. Scroll down to "Commit changes" section
7. Type commit message: "Add portfolio website"
8. Click **"Commit changes"** button

**Method B: Using Git Commands** (For developers)

```powershell
# Open PowerShell and run:

# 1. Navigate to Resume-Preparation folder
cd "c:\Quadrant-Repos\QMigrator_Modules\Web-Agents\Resume-Preparation"

# 2. Initialize Git
git init

# 3. Add your file
git add index.html

# 4. Commit
git commit -m "Add portfolio website"

# 5. Add your GitHub repository (replace YOUR-USERNAME)
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git

# 6. Push to GitHub
git branch -M main
git push -u origin main
```

---

### **STEP 4: Enable GitHub Pages**

1. In your repository, click **"Settings"** tab (top right)
2. Look for **"Pages"** in the left sidebar (under "Code and automation")
3. Click **"Pages"**
4. Under **"Source"** section:
   - Branch: Select **"main"** from dropdown
   - Folder: Keep as **"/ (root)"**
5. Click **"Save"** button
6. Wait **1-2 minutes** for deployment

---

### **STEP 5: Get Your Live URL**

1. Stay on the Pages settings page
2. After 1-2 minutes, refresh the page
3. You'll see a green box at the top saying:
   ```
   ✅ Your site is live at https://YOUR-USERNAME.github.io/portfolio/
   ```
4. Click the **"Visit site"** button to view your portfolio

**Your Portfolio URL:**
```
https://YOUR-USERNAME.github.io/portfolio/
```

✅ **This URL is yours forever - FREE!**

---

## 📱 ADD TO LINKEDIN

### **Option 1: LinkedIn Profile Header**

1. Go to **https://linkedin.com** and login
2. Click on **"Me"** → **"View Profile"**
3. Click the **"Edit"** pencil icon (next to your profile picture)
4. Scroll to **"Contact Info"**
5. Under **"Websites"**, click **"Add"** or **"+"**
6. Select **"Portfolio"** or **"Personal Website"**
7. Paste your GitHub Pages URL:
   ```
   https://YOUR-USERNAME.github.io/portfolio/
   ```
8. Click **"Save"**

### **Option 2: LinkedIn Featured Section**

1. On your LinkedIn profile, scroll to **"Featured"** section
2. Click **"➕ Add featured"**
3. Select **"Link"**
4. Paste your portfolio URL
5. Add title: **"Professional Portfolio & Resume"**
6. Add description: **"Interactive portfolio showcasing AI/ML projects and experience"**
7. Click **"Save"**

### **Option 3: LinkedIn About/Summary**

1. Edit your **"About"** section
2. Add at the end:
   ```
   📊 View my complete portfolio: https://YOUR-USERNAME.github.io/portfolio/
   ```
3. Save changes

---

## 🔄 HOW TO UPDATE YOUR PORTFOLIO

When you want to add new projects or update content:

### **Easy Method (No Git Required):**

1. Go to your GitHub repository: `https://github.com/YOUR-USERNAME/portfolio`
2. Click on **`index.html`** file
3. Click the **pencil icon** (✏️ Edit) in the top right
4. Make your changes to the HTML
5. Scroll down to **"Commit changes"**
6. Type what you changed (e.g., "Added new project")
7. Click **"Commit changes"** button
8. Wait 1-2 minutes - your website updates automatically!

### **Using Git (For developers):**

```powershell
# 1. Make changes to index.html locally
# 2. Commit and push:

git add index.html
git commit -m "Updated portfolio with new projects"
git push
```

Your changes go live in 1-2 minutes automatically!

---

## 💡 LOCAL TESTING

Before deploying, test your portfolio locally:

**Windows:**
```powershell
# Navigate to folder
cd "c:\Quadrant-Repos\QMigrator_Modules\Web-Agents\Resume-Preparation"

# Open in browser
start index.html
```

Or simply **double-click** `index.html` file to open in browser.

---

## 🎨 CUSTOMIZATION GUIDE

To customize colors, content, or styling:

1. Open `index.html` in any text editor (Notepad, VS Code, etc.)
2. Find the section you want to edit
3. Make changes and save
4. Upload to GitHub (see "How to Update" section above)

**Common Customizations:**

- **Change Colors:** Edit CSS variables in `:root` section (around line 15-25)
- **Update Content:** Edit HTML text in `<section>` tags (around line 200+)
- **Add Projects:** Copy existing `<div class="project-card">` block and modify
- **Change Contact Info:** Edit header section (around line 100-120)

---

## 📄 CONVERTING TO PDF

Need a PDF version for email attachments?

1. Open your portfolio in browser (local or deployed)
2. Press **Ctrl + P** (Windows) or **Cmd + P** (Mac)
3. Destination: Select **"Save as PDF"**
4. Settings:
   - Layout: Portrait
   - Paper size: A4
   - Margins: Default
   - Background graphics: ✅ Enabled
5. Click **"Save"**

Your PDF resume is ready!

---

## ✅ CHECKLIST BEFORE SHARING

Before sharing your portfolio link:

- [ ] Website loads correctly in browser
- [ ] All contact information is accurate
- [ ] LinkedIn URL is correct
- [ ] Email address is working
- [ ] Phone number is current
- [ ] All achievement numbers are accurate (98%, 95%, etc.)
- [ ] Project descriptions are up to date
- [ ] No typos or grammatical errors
- [ ] Test on mobile phone
- [ ] Test on different browsers (Chrome, Firefox, Edge)

---

## 🌟 SHARING YOUR PORTFOLIO

### **Where to Share:**

1. **LinkedIn Profile** - Featured section, About, Contact info
2. **Email Signature** - Add portfolio link
3. **Resume Header** - Include URL below contact info
4. **Job Applications** - Paste link in application forms
5. **Cover Letters** - Mention portfolio link
6. **Networking Events** - Share QR code to portfolio
7. **Business Cards** - Print portfolio URL

### **Email Signature Example:**

```
M. Siva Naga Raju
Senior Technical Analyst | AI Solutions Architect
📧 siva.m504504@gmail.com | 📱 +91-8985111673
🌐 Portfolio: https://YOUR-USERNAME.github.io/portfolio/
💼 LinkedIn: linkedin.com/in/siva-nagaraju-molabanti-b9883a185
```

---

## 💎 BONUS: Custom Domain (Optional)

Want `www.sivanaga.com` instead of GitHub subdomain?

**Cost:** ~$10-15/year for domain

### **Steps:**

1. **Buy Domain** from:
   - Namecheap: https://www.namecheap.com
   - GoDaddy: https://www.godaddy.com
   - Google Domains: https://domains.google

2. **Configure GitHub Pages:**
   - In your repo: Settings → Pages
   - Under "Custom domain", enter your domain
   - Click "Save"

3. **Update DNS Settings:**
   - In your domain registrar, add these DNS records:
   ```
   Type: A
   Host: @
   Value: 185.199.108.153
   
   Type: A
   Host: @
   Value: 185.199.109.153
   
   Type: A
   Host: @
   Value: 185.199.110.153
   
   Type: A
   Host: @
   Value: 185.199.111.153
   
   Type: CNAME
   Host: www
   Value: YOUR-USERNAME.github.io
   ```

4. Wait 24-48 hours for DNS propagation

---

## 🔧 TROUBLESHOOTING

### **Issue: Website not loading after enabling Pages**
- **Solution:** Wait 2-5 minutes, then refresh. GitHub needs time to deploy.

### **Issue: 404 Page Not Found**
- **Solution:** Make sure file is named exactly `index.html` (lowercase)
- Check that Pages is enabled with "main" branch selected

### **Issue: Changes not showing**
- **Solution:** Clear browser cache (Ctrl + Shift + R)
- Wait 1-2 minutes after committing changes

### **Issue: CSS/Styling looks broken**
- **Solution:** Make sure entire HTML file uploaded correctly
- Check browser console for errors (F12 → Console tab)

### **Issue: Can't push to GitHub**
- **Solution:** Check your Git credentials
- Use Personal Access Token instead of password for authentication

---

## 📱 BROWSER COMPATIBILITY

Tested and working on:
- ✅ Google Chrome (Recommended)
- ✅ Microsoft Edge
- ✅ Mozilla Firefox
- ✅ Safari (Mac/iOS)
- ✅ Mobile browsers (Android/iOS)
- ✅ Internet Explorer 11+ (basic support)

---

## 📊 FEATURES

### **Design Features:**
- ✨ Modern gradient backgrounds
- 🎨 Professional purple/blue color scheme
- 📱 Fully responsive (mobile, tablet, desktop)
- ⚡ Fast loading (single HTML file)
- 🎯 SEO optimized with meta tags
- 🖨️ Print-friendly CSS
- 🔄 Smooth scroll animations
- 📈 Interactive statistics cards
- 🎭 Hover effects on all interactive elements

### **Content Sections:**
- 👤 Professional header with contact info
- 📝 Summary with achievement statistics
- 💼 Skills organized by category
- 🏢 Work experience timeline
- 🤖 6 AI Agents detailed descriptions
- 🎯 Client projects (Nike, eBay, UHG, etc.)
- 🎓 Education background
- 📜 Certifications

### **Interactive Elements:**
- 📍 Sticky navigation bar
- 🔝 Scroll-to-top button
- ✨ Fade-in animations on scroll
- 🎨 Hover effects on cards
- 🔗 Smooth section scrolling
- 📧 Clickable contact links

---

## 📈 ANALYTICS (Optional)

Want to track who views your portfolio?

### **Add Google Analytics:**

1. Create account at: https://analytics.google.com
2. Get your tracking ID (format: G-XXXXXXXXXX)
3. Add this code before `</head>` tag in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

Now you can see:
- How many people visit
- Where they're from
- Which sections they view
- Time spent on portfolio

---

## 🎯 BEST PRACTICES

### **Keep It Updated:**
- ✅ Add new projects every 3-6 months
- ✅ Update skills as you learn new technologies
- ✅ Refresh achievement numbers
- ✅ Remove outdated projects
- ✅ Check all links quarterly

### **Content Guidelines:**
- ✅ Keep descriptions concise and impactful
- ✅ Use numbers and percentages (98%, $2M, etc.)
- ✅ Highlight Fortune 500 clients
- ✅ Focus on results, not just tasks
- ✅ Use action verbs (Led, Designed, Achieved, Built)

### **Technical Best Practices:**
- ✅ Test on mobile devices regularly
- ✅ Ensure all external links open in new tab
- ✅ Keep page load fast (single HTML is perfect)
- ✅ Validate HTML if making custom changes
- ✅ Backup your `index.html` file locally

---

## 🚀 QUICK START SUMMARY

**Complete Deployment in 5 Minutes:**

1. **Create GitHub account** → https://github.com
2. **Create repository** → Name it "portfolio", make it Public
3. **Upload `index.html`** → Drag and drop file
4. **Enable Pages** → Settings → Pages → Select "main" branch → Save
5. **Get your URL** → https://YOUR-USERNAME.github.io/portfolio/
6. **Add to LinkedIn** → Profile → Contact Info → Add website URL

**Done! Your portfolio is live forever (FREE)** 🎉

---

## 📞 SUPPORT & CONTACT

**For issues with the portfolio website:**
- 📧 Email: siva.m504504@gmail.com
- 💼 LinkedIn: linkedin.com/in/siva-nagaraju-molabanti-b9883a185

**For GitHub Pages help:**
- 📚 Official Docs: https://docs.github.com/pages
- 💬 GitHub Community: https://github.community

**For Git help:**
- 📖 Git Documentation: https://git-scm.com/doc
- 🎓 GitHub Learning Lab: https://lab.github.com

---

## 📝 VERSION HISTORY

- **v1.0** (April 2026) - Initial portfolio website created
  - Professional modern design
  - 6 AI agents documented
  - Fortune 500 client projects
  - Fully responsive layout
  - SEO optimized

---

## 🎓 LEARNING RESOURCES

Want to customize further? Learn these:

- **HTML Basics:** https://www.w3schools.com/html/
- **CSS Styling:** https://www.w3schools.com/css/
- **GitHub Pages:** https://pages.github.com
- **Git Tutorial:** https://git-scm.com/book/en/v2
- **Markdown Guide:** https://www.markdownguide.org

---

## ⭐ FINAL TIPS

1. **Share Immediately** - Don't wait for "perfect", share your portfolio now!
2. **Get Feedback** - Ask colleagues to review and suggest improvements
3. **Track Results** - Note if portfolio leads to interviews/opportunities
4. **Stay Consistent** - Update regularly (set calendar reminder every 3 months)
5. **Be Proud** - You've built something professional - showcase it!

---

**🎉 Your portfolio is ready to impress recruiters and hiring managers!**

**Next Steps:**
1. ✅ Deploy to GitHub Pages (5 minutes)
2. ✅ Add link to LinkedIn profile
3. ✅ Share with your network
4. ✅ Start getting interview calls!

---

**Last Updated:** April 10, 2026  
**Created by:** M. Siva Naga Raju  
**Tech Stack:** HTML5, CSS3, JavaScript (Vanilla)  
**Hosting:** GitHub Pages (FREE Forever)
