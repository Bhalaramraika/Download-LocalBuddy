# Local Buddy - Direct App Download Website

Official download website for the Local Buddy Android application. This website provides a direct download link for the Local Buddy APK file.

## About Local Buddy

Local Buddy connects households with trusted students and youth for errands and daily tasks in Tier-2 and Tier-3 cities across India. The app features:

- **Gamified Experience**: Earn Karma Points for every service with exclusive animations and reward tracking
- **Verified & Secure**: Cryptographically signed app builds ensuring safety for both helpers and users
- **Faster Updates**: Direct APK distribution means instant access to new features without app store delays
- **Optimized Performance**: Built specifically for Tier-2/3 network conditions

## Website Features

The website includes:

1. **Hero Section**: Main download CTA with app preview and smooth animations
2. **Features Section**: Highlighting why users should choose the app with animated cards
3. **Income Calculator**: Interactive slider to calculate earnings (₹400/hour base rate)
4. **Installation Guide**: Step-by-step instructions for installing the APK
5. **Support Section**: Help and FAQ access
6. **Responsive Design**: Mobile-first design that works on all devices
7. **Dark Mode**: Automatic dark mode support
8. **Advanced Animations**: High-level animations throughout including slide-in, fade, bounce, and shimmer effects

## Download Links

The APK download is hosted on MediaFire:
- **Direct Download**: [LocalBuddy.apk](https://www.mediafire.com/file/zmafddx601he5j0/LocalBuddy.apk/file?dkey=c5yye4rqp1y&r=1899)
- **File Size**: 20 MB
- **Required Android Version**: 8.0+
- **Current Version**: v1.0.0

## Installation Instructions

1. **Download the APK**: Click any download button on the website
2. **Enable Unknown Sources**: 
   - Go to Settings → Security
   - Enable "Install from Unknown Sources" or "Install Unknown Apps" for your browser
3. **Install the App**: Open the downloaded APK file and follow the prompts
4. **Start Using**: Create your account and connect with local helpers

## Technology Stack

- **HTML5**: Semantic markup
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Google Fonts**: Inter font family
- **Material Symbols**: Icon library
- **Vanilla JavaScript**: Smooth scrolling and interaction handling

## File Structure

```
Download-LocalBuddy/
├── index.html          # Main website file
├── README.md          # This file
└── Readme.txt         # Original readme
```

## Usage

Simply open the `index.html` file in any modern web browser, or deploy to any web hosting service. The website is completely self-contained with no build process required.

### Local Development

To run locally:
```bash
# Option 1: Open directly
open index.html

# Option 2: Use Python's built-in server
python -m http.server 8000

# Option 3: Use Node.js http-server
npx http-server
```

Then navigate to `http://localhost:8000` in your browser.

## Deployment

This website can be deployed to any static hosting service:

- **GitHub Pages**: Push to a repository and enable GitHub Pages
- **Netlify**: Drag and drop the folder or connect to Git
- **Vercel**: Deploy with a single command
- **Firebase Hosting**: Use Firebase CLI
- **AWS S3**: Upload as static website

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Security

- All APK files are cryptographically signed
- Downloads are served over HTTPS via MediaFire
- No user data is collected on the website
- External links open in new tabs with `rel="noopener noreferrer"`

## License

© 2024 Local Buddy Inc. All rights reserved.

## Contact

For support or questions, use the contact options on the website or reach out through the in-app support system.
