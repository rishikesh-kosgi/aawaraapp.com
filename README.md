# Aawara - Static Website

A modern, luxury-inspired static website for your app with a home page and privacy policy.

## Structure

```
AawaraWeb/
├── index.html              # Home page
├── privacy-policy.html     # Privacy policy page
├── style.css              # Main stylesheet
├── assets/                # Images folder (to be created)
└── README.md
```

## Features

- **Modern Luxury Design**: Inspired by premium brands like Mercedes-Benz
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile
- **Clean Code**: Well-organized HTML and CSS
- **Privacy Policy**: Comprehensive sample privacy policy included
- **No JavaScript Required**: Pure HTML and CSS for maximum compatibility
- **Image-Only**: No videos, only images as requested

## customization Guide

### 1. Update App Information

**On index.html:**
- Change "Aawara" to your app name in:
  - Navigation logo
  - Hero section title
  - Footer

- Update feature descriptions in the "Features" section (lines ~50-80)
- Modify showcase content to describe your app better (lines ~85-105)
- Update statistics (users count, rating, etc.) in the "Statistics" section (lines ~110-130)

### 2. Add Your Images

Create an `assets` folder in the root directory and add these images:

Required images:
- `hero-image.png` - Large hero section image (recommended size: 500x600px)
- `showcase-image.png` - Showcase section image (recommended size: 450x500px)
- `feature-1.png` - Feature icon (recommended size: 80x80px)
- `feature-2.png` - Feature icon
- `feature-3.png` - Feature icon
- `feature-4.png` - Feature icon

**Image Tips:**
- Use high-quality PNG or JPG images
- Keep file sizes optimized (<200KB each)
- Use consistent aspect ratios for feature icons
- Ensure images are centered and well-composed

### 3. Update Privacy Policy

Edit `privacy-policy.html`:
- Replace "Your Address Here", "Your Phone Number", and "privacy@aawara.com" with actual contact information
- Update the "Last Updated" date
- Customize privacy policy sections based on your actual data practices
- Add your company/app specific details

### 4. Update Footer Information

In both HTML files, update:
- Company address and contact details
- Social media links
- Any additional footer links

### 5. Colors & Styling

Edit `style.css` to change the color scheme:
- `--primary-color`: Main text color (currently #1a1a1a - dark gray/black)
- `--secondary-color`: Background white
- `--accent-color`: Gold highlights (currently #c79a44)
- `--medium-gray`: Secondary text color

## Deployment

This is a static website - you can host it anywhere:

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push all files to the repo
3. Enable GitHub Pages in repository settings
4. Your site will be live at: `username.github.io/repo-name`

### Option 2: Netlify (Free with custom domain)
1. Go to netlify.com
2. Drag and drop your folder
3. Site goes live instantly

### Option 3: Any Web Host
- Upload files via FTP or file manager
- No build process needed

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## File Descriptions

- **index.html** - Home page with hero, features, showcase, stats, and CTA sections
- **privacy-policy.html** - Comprehensive privacy policy with 12 sections
- **style.css** - Responsive CSS with mobile-first design
- **assets/** - Folder for storing images (you need to create and populate this)

## Next Steps

1. Create the `assets` folder
2. Add your images with the filenames mentioned above
3. Update all placeholder text with your actual app information
4. Customize colors if needed
5. Test on multiple devices
6. Deploy to your chosen hosting platform

## Contact

Update the privacy policy contact section with your actual contact information.

---

**Note**: This is a template. Customize the content to accurately reflect your app and business practices.
