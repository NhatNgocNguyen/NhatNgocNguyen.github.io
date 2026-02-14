# Academic Profile Website

A simple, aesthetic academic profile website with sections for About, News, Publications, CV, and Contact.

## Features

- **Home Page**: Combined About and News sections
- **Publications**: Organized by year with links to papers
- **CV**: Education and Experience sections with awards
- **Contact**: Contact information and social links
- **Dark Theme**: Toggle between light and dark modes with preference saved to browser
- Clean, minimalist design with elegant typography
- Fully responsive layout
- Easy to customize

## Customization

### Basic Information
1. Replace "Your Name" in all HTML files with your actual name
2. Update "Your Field" with your research area
3. Add your university/institution information
4. **Add your profile photo**: Replace `avatar.jpg` with your own photo (recommended: 400x400px or larger, square format)

### Content Updates

**Home Page (index.html)**:
- Update the hero section with your title and affiliation
- Replace About section text with your bio
- Add/remove news items as needed

**Publications (publications.html)**:
- Add your papers organized by year
- Update authors, venues, and links

**CV (cv.html)**:
- Add your education details
- Add your experience/positions
- Update awards and honors

**Contact (contact.html)**:
- Add your email address
- Add your office location
- Update social media links

### Styling
- Colors and fonts can be customized in `styles.css`
- Look for the `:root` section at the top of the CSS file
- Current color scheme uses warm earth tones with Crimson Pro and Archivo fonts

## Deploying to GitHub Pages

1. **Create a new repository on GitHub**
   - Go to github.com and create a new repository
   - Name it `your-username.github.io` (or any name you prefer)

2. **Upload your files**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/your-username/your-repo-name.git
   git push -u origin main
   ```

3. **Enable GitHub Pages**
   - Go to your repository settings
   - Navigate to "Pages" in the sidebar
   - Under "Source", select "main" branch
   - Click "Save"

4. **Access your site**
   - Your site will be live at `https://your-username.github.io/your-repo-name/`
   - It may take a few minutes for the site to go live

## File Structure

```
├── index.html          # Home page (About + News)
├── publications.html   # Publications page
├── cv.html            # CV page (Education + Experience)
├── contact.html       # Contact page
├── styles.css         # All styling
└── README.md          # This file
```

## Browser Support

Works on all modern browsers including:
- Chrome
- Firefox
- Safari
- Edge

## License

Free to use for academic purposes. Customize as needed.
