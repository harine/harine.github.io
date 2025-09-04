# Website Setup Guide

## Quick Start

Your website is now ready to be customized! Here's what you need to do:

### 1. Update Personal Information

**Edit `_config.yml`:**
- Change `name: Your Name` to your actual name
- Update `email: your-email@example.com` with your email
- Update `github: your-github-username` with your GitHub username
- Update `linkedin: your-linkedin-profile` with your LinkedIn profile
- Add any other social media links you want

**Edit `_layouts/default.html`:**
- Replace the placeholder bio text with your actual introduction
- Update the social media links in the header section

### 2. Add Your Profile Photo

1. Replace `images/your-photo.jpg` with your actual profile photo
2. Recommended size: 400x400 pixels (square aspect ratio)
3. The image will automatically be used as your avatar

### 3. Add Your Content

**Create blog posts:**
1. Add markdown files to the `_posts` directory
2. Use the format: `YYYY-MM-DD-title.md`
3. Include proper front matter (see the sample post for reference)

**Categories for posts:**
- `projects`: Shows in the main "Projects" section
- `professional`: Shows in the "Professional Work" section
- `personal`: Shows in the "Personal Projects" section

### 4. Add Images

1. Add your images to the `images` folder
2. Reference them in posts with `/images/filename.jpg`
3. For thumbnails, the system will automatically look in the `tn/` folder

### 5. Deploy to GitHub Pages

1. Push your changes to GitHub
2. Go to your repository settings
3. Enable GitHub Pages in the Pages section
4. Your site will be available at `https://yourusername.github.io`

### 6. Optional: Custom Domain

If you have a custom domain:
1. Update the `CNAME` file with your domain
2. Update the `url` in `_config.yml`
3. Configure DNS settings with your domain provider

## File Structure

```
├── _config.yml          # Site configuration
├── _layouts/
│   └── default.html     # Main layout template
├── _posts/              # Blog posts (markdown files)
├── images/              # Images and photos
├── style.scss           # Custom styling
└── CNAME                # Custom domain (if applicable)
```

## Need Help?

- Check the [Jekyll documentation](https://jekyllrb.com/docs/)
- Look at the sample post in `_posts/2024-01-01-welcome.md`
- The design is based on [Jon Barron's website](https://jonbarron.info/)
