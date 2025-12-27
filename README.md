# JustFed Website

A modern, minimalistic, empathic static website for the JustFed iOS app.

## Overview

This website is built with:
- **Tailwind CSS** (via CDN) for styling
- **Vanilla JavaScript** for simple interactions
- **Responsive design** for mobile and desktop
- **Privacy-first messaging** throughout

## File Structure

```
JustFedWeb/
├── index.html          # Main landing page
├── privacy.html        # Privacy policy page
├── img/               # App screenshots
│   ├── main.png       # Main app screen
│   ├── logging.png    # Logging feature
│   ├── pair.png       # Pairing feature
│   ├── dynamic.png    # Live Activity
│   ├── insights.png   # 7-day insights
│   └── welcome.png    # Welcome screen
└── README.md          # This file
```

## Features

### Home Page (index.html)
- **Hero Section**: App introduction with CTA buttons
- **Features Section**: 4 key features with screenshots
- **Insights Section**: Explanation of 7-day insights
- **Privacy Section**: Key privacy commitments
- **CTA Section**: Final call-to-action
- **Footer**: Navigation and contact info

### Privacy Page (privacy.html)
- Comprehensive privacy policy
- Clear, parent-friendly language
- Explains data storage and CloudKit sync
- No legal jargon overload

## Customization

### Update App Store Links
Search for `href="#"` in both HTML files and replace with your actual App Store URL.

### Change Colors
The color scheme uses Tailwind's indigo/purple palette. To customize:

1. Edit the `tailwind.config` in the `<script>` tag:
```javascript
tailwind.config = {
    theme: {
        extend: {
            colors: {
                primary: '#6366f1',    // Change this
                secondary: '#8b5cf6',  // Change this
            }
        }
    }
}
```

### Update Contact Email
Replace `support@justfed.app` with your actual support email throughout both files.

### Add Analytics (Optional)
If you want to add privacy-respecting analytics, add the script before `</head>` in both files.

## Deployment

### Option 1: GitHub Pages
1. Create a GitHub repository
2. Push the JustFedWeb folder contents
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://username.github.io/repo-name`

### Option 2: Netlify
1. Drag and drop the JustFedWeb folder to [Netlify Drop](https://app.netlify.com/drop)
2. Your site will be live instantly with a custom URL

### Option 3: Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in the JustFedWeb directory
3. Follow the prompts

### Option 4: Traditional Web Host
Upload the entire JustFedWeb folder contents to your web host via FTP/SFTP.

## Performance

- **No build step required** - Pure static HTML
- **Fast loading** - Tailwind CSS loaded via CDN with caching
- **Optimized images** - Consider compressing PNGs further for faster loading
- **Minimal JavaScript** - Only ~20 lines for mobile menu toggle

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## SEO Optimization

To improve SEO, consider adding:
1. Sitemap.xml
2. robots.txt
3. Open Graph meta tags for social sharing
4. More descriptive meta descriptions
5. Schema.org markup for app listings

## Accessibility

The site includes:
- Semantic HTML elements
- Proper heading hierarchy
- Alt text for images (update as needed)
- Keyboard navigation support
- Sufficient color contrast

## Future Enhancements

Consider adding:
- App Store badge images (official Apple badges)
- Video demo of the app
- Testimonials section
- FAQ section
- Blog for parenting tips
- Newsletter signup

## License

Update with your license information.

## Support

For questions or issues, contact: support@justfed.app
