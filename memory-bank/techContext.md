# Tech Context: Distill & Taste Website

## Technology Stack

This is a static, client-side web application built using standard web technologies:

### Frontend Technologies

- **HTML5**: Semantic markup for structure and accessibility
- **CSS3**: Custom styling with CSS variables, flexbox, and grid for responsive layout
- **JavaScript (Vanilla)**: Client-side scripting for interactivity (no frameworks or libraries)

### Key Dependencies and Tools

- **Images**: Sourced from Pexels (stock photo service) with proper attribution and fallbacks
- **Fonts**: Custom font file (`oracles.woff`) for branding, with system font fallbacks
- **Development Tools**: Standard web browser developer tools for testing and debugging

## Development Environment

- **Local Development**: Served via local file system or simple HTTP server
- **Version Control**: Git repository (origin: https://github.com/Rekotek/Distill-And-Taste.git)
- **Editor/IDE**: Compatible with VS Code or similar editors
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge) with fallbacks for older versions

## Technical Constraints and Considerations

- **Static Site**: No server-side processing or database required
- **Performance**: Optimized for fast loading with inline CSS/JS to minimize HTTP requests
- **Accessibility**: Follows WCAG guidelines with semantic HTML, proper alt text, and keyboard navigation
- **Mobile Responsiveness**: CSS media queries for tablet and mobile breakpoints
- **Internationalization**: JavaScript-based i18n system for Russian and Latvian content switching

## Architecture Decisions

- **Inline CSS**: All styles embedded in HTML for simplicity and to avoid external file dependencies
- **Vanilla JavaScript**: Chosen to keep the project lightweight and dependency-free
- **Progressive Enhancement**: Core functionality works without JavaScript, with enhancements layered on top
- **Image Optimization**: Uses responsive images with `srcset` for different screen sizes and formats

## Security and Privacy

- **No User Data Collection**: Static site with no forms or data storage
- **External Resources**: Images loaded from Pexels (consider implementing local fallbacks for offline use)
- **HTTPS**: Should be served over HTTPS in production for security
- **Content Security Policy**: Could be implemented if deploying to a web server

## Deployment and Hosting

- **Static Hosting**: Suitable for services like GitHub Pages, Netlify, or Vercel
- **Build Process**: No build step required - direct deployment of HTML file
- **Domain and CDN**: Can use custom domain with CDN for global distribution and caching

## Maintenance and Updates

- **Content Updates**: Manual editing of HTML file for content changes
- **Translation Management**: Updates to JavaScript dictionary object for new languages or corrections
- **Image Updates**: Replace image URLs or implement local image hosting for better control
- **Performance Monitoring**: Use browser dev tools and online performance testers (e.g., Google PageSpeed Insights)

## Future Technical Considerations

- **Framework Migration**: Could migrate to React/Vue if more complex interactivity is needed
- **Build Tools**: Consider adding tools like Webpack or Vite for asset optimization if project grows
- **Testing**: Implement automated testing with tools like Jest or Cypress for JavaScript functionality
- **Analytics**: Add privacy-friendly analytics (e.g., Plausible) if user behavior tracking is desired
