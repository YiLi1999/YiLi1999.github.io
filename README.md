# Yi Li - Academic Homepage

Personal academic website for Yi Li, PhD candidate at Peking University.

**Live Website:** https://YiLi1999.github.io

## File Structure

```
├── index.html          # Home / About page
├── research.html       # Research interests and projects
├── publications.html   # List of publications
├── talks.html          # Talks and presentations
├── cv.html             # Curriculum Vitae
├── contact.html        # Contact information
├── style.css           # Shared stylesheet
└── README.md           # This file
```

## Local Preview

### Option 1: Direct Browser Opening
Simply double-click `index.html` to open it in your web browser.

### Option 2: Using VS Code Live Server (Recommended)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

### Option 3: Using Python
```bash
# Python 3
python -m http.server 8000

# Then open http://localhost:8000 in your browser
```

## Customization Guide

### 1. Personal Information
Edit each HTML file to update your information:
- **Name**: Search and replace "Yi Li" and "李逸"
- **Email**: Search and replace "yili@stu.pku.edu.cn"
- **Phone**: Update your phone number

### 2. Profile Photo
To add your photo:
1. Place your photo (e.g., `photo.jpg`) in the same directory as the HTML files
2. In `index.html`, find the commented line:
   ```html
   <!-- <img src="photo.jpg" alt="Yi Li" class="profile-photo"> -->
   ```
3. Uncomment it by removing `<!--` and `-->`:
   ```html
   <img src="photo.jpg" alt="Yi Li" class="profile-photo">
   ```

### 3. Social Links
Update links in multiple places:
- `index.html` (Hero section and Quick Links)
- `contact.html` (Online Presence section)
- `publications.html` (Google Scholar link)

Replace placeholder URLs:
- Google Scholar: Update the scholar.google.com URL
- LinkedIn: Replace with your LinkedIn profile URL
- Twitter/X: Replace with your Twitter/X profile URL
- GitHub: Add your GitHub profile URL in `contact.html`

### 4. Adding a CV PDF
1. Place your CV PDF file (e.g., `CV.pdf`) in the directory
2. In `cv.html`, find and update:
   ```html
   <a href="[Link to your CV PDF]" target="_blank">
   ```
   Change to:
   ```html
   <a href="CV.pdf" target="_blank">
   ```

### 5. Publications
Update `publications.html`:
- Edit the publication list with your actual papers
- Update citation statistics (Total Citations, h-index, i10-index)
- Keep the most recent publications at the top

### 6. Research Content
Update `research.html`:
- Edit research interest descriptions
- Update project information
- Add or modify research visits

## GitHub Pages Deployment

### Automatic Deployment (Recommended)

1. **Create a GitHub Repository**
   - Go to [GitHub](https://github.com)
   - Create a new repository named `YiLi1999.github.io` (or your preferred name)
   - Make it public

2. **Push Your Files**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Under "Source", select "Deploy from a branch"
   - Select the `main` branch and `/ (root)` folder
   - Click Save

4. **Access Your Site**
   - Your site will be live at `https://YOUR_USERNAME.github.io` (or `YOUR_REPO` if named differently)
   - It may take a few minutes for the site to be available

### Custom Domain (Optional)

If you want to use a custom domain (e.g., `yourname.com`):

1. In your repository Settings > Pages, add your custom domain
2. Configure your DNS records with your domain provider
3. Wait for DNS propagation (can take up to 24-48 hours)

## Browser Compatibility

This website is designed to work on:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome for Android)

## Technologies Used

- **HTML5** - Page structure
- **CSS3** - Styling and layout
- **Font Awesome 6.4** - Icons (via CDN)
- **Google Fonts** - System fonts for performance

No build tools, frameworks, or JavaScript dependencies required.

## License

This template is based on MIT License. Feel free to modify and use it for your own academic homepage.

---

*Last updated: March 2026*
