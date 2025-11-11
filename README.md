# Auglaize County Department of Job & Family Services Website

Official website for the Auglaize County Department of Job and Family Services, providing information and resources for public assistance, child support, children services, and workforce development.

## Features

- ✅ **WCAG 2.2 AA Compliant** - Fully accessible website meeting Level AA standards
- 🎨 **USWDS Design System** - Built with U.S. Web Design System components
- 📱 **Fully Responsive** - Optimized for mobile, tablet, and desktop
- ⚡ **Fast Performance** - Optimized assets and delivery
- 🔒 **Security Headers** - Enhanced security with proper HTTP headers

## WCAG 2.2 AA Compliance

This website has been built to meet WCAG 2.2 Level AA accessibility standards, including:

- Proper color contrast ratios (4.5:1 minimum for normal text)
- Keyboard navigation support
- Screen reader compatibility with proper ARIA labels
- Focus indicators for all interactive elements
- Minimum touch target sizes (24x24px)
- Semantic HTML structure
- Alternative text for images
- Skip navigation links
- Reduced motion support
- High contrast mode support

## Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Design System**: U.S. Web Design System (USWDS) 3.7.1
- **Icons**: Font Awesome 6.4.0
- **Server**: Node.js with Express
- **Hosting**: Railway

## Local Development

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm start
   ```

3. Open your browser to `http://localhost:3000`

## Deployment

This site is configured for deployment on Railway:

1. Connect your GitHub repository to Railway
2. Railway will automatically detect the configuration
3. Deploy with a single click

### Environment Variables

No environment variables are required for basic deployment.

### Custom Domain

To use a custom domain:
1. Go to your Railway project settings
2. Add your custom domain
3. Update your DNS records as instructed

## Project Structure

```
auglaizejfs/
├── index.html          # Main HTML file
├── styles.css          # Custom styles
├── server.js           # Express server
├── package.json        # Node.js dependencies
├── railway.json        # Railway configuration
├── .gitignore          # Git ignore rules
├── public/             # Static assets
├── logo.png            # Main logo
├── logo-white.png      # Footer logo
├── hero.png            # Hero background image
└── favicon_1.ico       # Favicon
```

## Accessibility Testing

To test accessibility:

1. **Automated Testing**:
   - Use axe DevTools browser extension
   - Use WAVE browser extension
   - Use Lighthouse in Chrome DevTools

2. **Manual Testing**:
   - Test keyboard navigation (Tab, Enter, Escape, Arrow keys)
   - Test with screen readers (NVDA, JAWS, VoiceOver)
   - Test color contrast with tools
   - Test at 200% zoom
   - Test on mobile devices

## Browser Support

- Chrome (latest 2 versions)
- Firefox (latest 2 versions)
- Safari (latest 2 versions)
- Edge (latest 2 versions)
- Mobile Safari (iOS 12+)
- Chrome for Android (latest)

## Performance

- Compression enabled (gzip)
- Static asset caching
- Optimized images
- Minified CSS delivery via CDN

## Security

Security headers implemented:
- `X-Content-Type-Options: nosniff`
- `X-Frame-Options: SAMEORIGIN`
- `X-XSS-Protection: 1; mode=block`
- `Referrer-Policy: strict-origin-when-cross-origin`

## Support

For technical support or questions:
- **Email**: AUGLAIZE_COUNTY_JFS@jfs.ohio.gov
- **Phone**: 567-242-2700

## License

© 2025 Auglaize County Department of Job & Family Services. All rights reserved.
