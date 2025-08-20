# Ryan Shook - Professional Portfolio Website

**Live Site:** [https://ryanshook.org](https://ryanshook.org)

## Overview

Professional portfolio website for Ryan Shook, Executive Director of Digital Strategy & Campuses at Woodlands Church. Showcases expertise in AI automation, nonprofit technology, donor development, and digital ministry solutions.

## Project Structure

```
ryanshook.github.io/
├── index.html              # Main website file
├── robots.txt              # SEO crawling instructions
├── sitemap.xml             # SEO sitemap
├── CNAME                   # Custom domain configuration
├── images/                 # Website images
│   ├── ryan.jpg            # Main profile photo (hero section)
│   ├── Ryan Speaking.jpg   # Speaking section image
│   ├── work.jpg            # Testimonials section image
│   ├── office.jpg          # Professional workspace image
│   └── gallery/            # Gallery images (unused)
├── assets/                 # Theme assets
│   ├── css/                # Stylesheets
│   ├── js/                 # JavaScript files
│   └── webfonts/           # Font files
└── story-template/         # Original theme files (reference only)
```

## Current Website Sections

1. **Hero Section** - Main introduction with profile photo and social links
2. **Speaking & Teaching** - Professional speaking experience and booking
3. **Core Competencies** - 4 key service areas:
   - AI & Automation Strategy
   - Donor Development
   - Nonprofit Analytics & Insights
   - Digital Ministry & Engagement
4. **Testimonials & Recognition** - Client testimonials and achievements
5. **Footer** - Contact information and call-to-action

## Key Features

### SEO Optimization
- Comprehensive meta tags with targeted keywords
- Structured data (Schema.org) for Person and ProfessionalService
- robots.txt following Google recommendations
- sitemap.xml for search indexing
- Optimized for nonprofit technology and AI automation keywords

### Professional Positioning
- **Title:** Executive Director of Digital Strategy & Campuses
- **Key Credentials:** NYT Bestselling Author, AI automation expert
- **Focus Areas:** Nonprofit technology, church growth, donor development
- **Experience:** 15+ years scaling faith-based organizations

### Technical Stack
- **Theme:** Story template (HTML5 UP)
- **Icons:** FontAwesome 5
- **Hosting:** GitHub Pages
- **Domain:** ryanshook.org
- **Analytics:** Google Analytics (if implemented)

## Design Principles

### Typography
- Improved letter spacing for better readability (`0.02em` for headers, `0.01em` for subtitles)
- Clean, professional font hierarchy
- Consistent spacing throughout

### Visual Design
- Clean, minimal design without animations
- Professional color scheme
- Responsive layout for all devices
- High-quality professional photography

### User Experience
- Fast loading (no animations)
- Clear navigation structure
- Mobile-responsive design
- Professional presentation focused on credibility

## Content Guidelines

### Core Messaging
- **Primary Value Prop:** Strategic technology implementation for nonprofits
- **Key Differentiators:** AI automation expertise, proven donor engagement results
- **Target Audience:** Nonprofit leaders, church executives, faith-based organizations

### Tone of Voice
- Professional and authoritative
- Results-focused and data-driven
- Approachable but expert-level
- Faith-informed but business-oriented

## Development Workflow

### Local Development
```bash
# Start local server from project root
python3 -m http.server 8000

# Or use any available port
python3 -c "import socket; s=socket.socket(); s.bind(('', 0)); print(s.getsockname()[1]); s.close()"
python3 -m http.server [PORT]
```

### Deployment
- **Automatic:** Push to `master` branch triggers GitHub Pages deployment
- **Manual:** Changes are live within 1-2 minutes of push
- **Custom Domain:** Configured via CNAME file

### Git Workflow
```bash
# Standard workflow
git add .
git commit -m "Descriptive commit message with 🤖 Generated with Claude Code signature"
git push origin master
```

## Important Files & Configurations

### Core Competencies Icons
Icons use FontAwesome 5 with specific theme classes:
- `fa-cog` (solid) - AI & Automation Strategy
- `fa-heart` (outline) - Donor Development  
- `fa-chart-bar` (solid) - Nonprofit Analytics & Insights
- `fa-desktop` (solid) - Digital Ministry & Engagement

### Image Requirements
- **Profile photo (ryan.jpg):** Professional headshot, optimized for web
- **Speaking photo (Ryan Speaking.jpg):** Stage/conference speaking image
- **Work photo (work.jpg):** Professional workplace/action shot
- **Format:** JPG preferred, optimized for web loading

### SEO Keywords (Primary)
- digital strategy
- AI automation
- nonprofit technology
- donor development
- church technology
- digital ministry
- nonprofit analytics
- faith-based organizations

## Common Tasks for AI Agents

### Content Updates
1. **Bio Updates:** Modify hero section text in `index.html`
2. **Achievements:** Update Recognition & Achievements section
3. **Core Competencies:** Modify service descriptions or add new ones
4. **Testimonials:** Replace or add new client testimonials

### Design Changes
1. **Typography:** Adjust letter spacing in `<style>` section
2. **Layout:** Modify section structure (be careful with theme classes)
3. **Images:** Replace images in `/images/` directory and update references
4. **Colors:** Work within existing theme color scheme

### SEO Improvements
1. **Meta Tags:** Update in `<head>` section for new keywords/positioning
2. **Structured Data:** Modify Schema.org JSON-LD for new services/credentials
3. **Content:** Add keyword-rich content while maintaining readability
4. **Technical:** Update robots.txt or sitemap.xml as needed

### Performance Optimization
1. **Images:** Compress/optimize images before adding
2. **Loading:** Avoid adding heavy animations or scripts
3. **Mobile:** Test responsive design on various screen sizes

## Maintenance Notes

### Regular Updates Needed
- Update "years of experience" annually
- Refresh achievements and testimonials periodically  
- Add new speaking engagements or credentials
- Update SEO meta descriptions for current positioning

### Technical Considerations
- Theme uses specific class structure - maintain compatibility
- FontAwesome icons may need `solid` class for proper display
- All paths should be relative to root directory
- Keep design clean and professional - avoid excessive animations

### Brand Consistency
- Maintain professional, results-focused messaging
- Emphasize measurable outcomes and specific expertise
- Keep nonprofit/church technology focus central
- Balance technical expertise with accessibility

## Contact & Support

**Website Owner:** Ryan Shook  
**Email:** contact@ryanshook.org  
**Role:** Executive Director of Digital Strategy & Campuses  
**Organization:** Woodlands Church  

For technical questions about this README or the website, refer to the commit history and GitHub issues for context on previous changes and decisions.

---

**Last Updated:** August 2025  
**Current Version:** Professional portfolio with SEO optimization and clean design