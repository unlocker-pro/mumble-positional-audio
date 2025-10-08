╔════════════════════════════════════════════════════════════════════════════╗
║                     MUMBLE SOFTWARE WEBSITE                                ║
║            Professional Voice Communication Platform                       ║
╚════════════════════════════════════════════════════════════════════════════╝

📋 TABLE OF CONTENTS
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
1. Introduction
2. File Structure
3. How to Run Locally
4. Customization Guide
   4.1 Changing Colors
   4.2 Updating Text & Content
   4.3 Replacing Links
   4.4 Modifying Keywords
5. Page Descriptions
6. Technical Features
7. Browser Support
8. Deployment
9. SEO Optimization
10. Troubleshooting
11. Credits & License


═══════════════════════════════════════════════════════════════════════════
1. INTRODUCTION
═══════════════════════════════════════════════════════════════════════════

This is a modern, responsive, multi-page website for Mumble Software.
The website features:
- Professional, clean design inspired by modern web standards
- Fully responsive layout (mobile, tablet, desktop)
- Smooth animations and transitions
- SEO-friendly structure with semantic HTML
- Cross-browser compatibility
- Fast loading times


═══════════════════════════════════════════════════════════════════════════
2. FILE STRUCTURE
═══════════════════════════════════════════════════════════════════════════

mumble4/
│
├── index.html          # Home page with hero section and features
├── about.html          # About page with mission, vision, and values
├── contact.html        # Contact page with Google Form integration
├── download.html       # Download page with platform information
├── style.css           # Main stylesheet for all pages
├── script.js           # JavaScript for interactivity and animations
└── README.txt          # This file


═══════════════════════════════════════════════════════════════════════════
3. HOW TO RUN LOCALLY
═══════════════════════════════════════════════════════════════════════════

OPTION 1: Direct File Opening
──────────────────────────────
1. Navigate to the project folder (mumble4/)
2. Double-click on "index.html"
3. The website will open in your default web browser
4. Navigate between pages using the navigation menu

OPTION 2: Using a Local Server (Recommended)
─────────────────────────────────────────────
For better testing, use a local server:

Method A - Python (if installed):
   • Open terminal/command prompt in the project folder
   • Run: python -m http.server 8000
   • Open browser and go to: http://localhost:8000

Method B - Node.js (if installed):
   • Install live-server: npm install -g live-server
   • Open terminal in project folder
   • Run: live-server
   • Browser will automatically open

Method C - VS Code:
   • Install "Live Server" extension
   • Right-click on index.html
   • Select "Open with Live Server"


═══════════════════════════════════════════════════════════════════════════
4. CUSTOMIZATION GUIDE
═══════════════════════════════════════════════════════════════════════════

4.1 CHANGING COLORS
───────────────────
Open style.css and find the :root section at the top (around line 11):

:root {
    --primary-color: #4361EE;     /* Main blue color */
    --secondary-color: #219EBC;   /* Accent teal color */
    --accent-color: #219EBC;      /* Same as secondary */
    --text-primary: #2B2D42;      /* Main text color */
    --text-secondary: #6C757D;    /* Secondary text color */
    --white: #FFFFFF;             /* White */
    --light-bg: #F8F9FA;          /* Light background */
    --border-color: #E9ECEF;      /* Border color */
}

Simply replace the hex color codes with your desired colors.
Changes will apply across the entire website automatically!


4.2 UPDATING TEXT & CONTENT
────────────────────────────
To change text content:

1. Open the relevant HTML file (index.html, about.html, etc.)
2. Find the text you want to change
3. Replace it with your new text
4. Save the file

Common sections to update:
• Hero titles and descriptions
• Feature descriptions
• About page content
• Footer information


4.3 REPLACING LINKS
────────────────────
Current important links in the website:

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
LINK TYPE              | CURRENT URL                                | WHERE TO FIND
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━
Official Website       | https://mumble133.info/                    | All pages
Google Form            | https://docs.google.com/forms/d/e/...      | contact.html
Download Link          | https://mumble133.info/download/           | download.html
GitHub Repository      | https://github.com/unlocker-pro/mumble133  | All pages
━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

To replace a link:
1. Use Find & Replace (Ctrl+H or Cmd+H) in your text editor
2. Find: [old URL]
3. Replace: [new URL]
4. Click "Replace All" for that file or all files


4.4 MODIFYING KEYWORDS
───────────────────────
Current focus keyword: "mumble software"
Location: index.html (hero section and meta tags)

To change:
1. Open index.html
2. Search for "mumble software"
3. Replace with your desired keyword
4. Update meta description if needed


═══════════════════════════════════════════════════════════════════════════
5. PAGE DESCRIPTIONS
═══════════════════════════════════════════════════════════════════════════

┌─────────────────────────────────────────────────────────────────────────┐
│ HOME PAGE (index.html)                                                  │
├─────────────────────────────────────────────────────────────────────────┤
│ • Hero section with animated floating cards                            │
│ • Feature showcase grid                                                 │
│ • About preview section                                                 │
│ • Statistics cards                                                      │
│ • Call-to-action section                                                │
│ • Keywords naturally integrated in content                              │
│ • Links to official site                                                │
└─────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────┐
│ ABOUT PAGE (about.html)                                                 │
├─────────────────────────────────────────────────────────────────────────┤
│ • Company story and background                                          │
│ • Mission and Vision sections                                           │
│ • Core values grid                                                      │
│ • Team statistics                                                       │
│ • Link back to home page                                                │
└─────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────┐
│ CONTACT PAGE (contact.html)                                             │
├─────────────────────────────────────────────────────────────────────────┤
│ • Professional contact form button                                      │
│ • Opens Google Form in new tab                                          │
│ • Contact information cards                                             │
│ • Alternative contact methods                                           │
│ • Link back to home page                                                │
└─────────────────────────────────────────────────────────────────────────┘

┌─────────────────────────────────────────────────────────────────────────┐
│ DOWNLOAD PAGE (download.html)                                           │
├─────────────────────────────────────────────────────────────────────────┤
│ • Prominent download button                                             │
│ • Platform compatibility information                                    │
│ • Feature highlights                                                    │
│ • System requirements                                                   │
│ • Installation guide                                                    │
│ • FAQ section                                                           │
│ • Link back to home page                                                │
└─────────────────────────────────────────────────────────────────────────┘


═══════════════════════════════════════════════════════════════════════════
6. TECHNICAL FEATURES
═══════════════════════════════════════════════════════════════════════════

✓ Responsive Design
  - Mobile-first approach
  - Breakpoints: 480px, 768px, 992px
  - Hamburger menu for mobile devices

✓ Modern CSS
  - CSS Variables for easy customization
  - Flexbox and Grid layouts
  - Smooth transitions and animations
  - Box-shadow and gradient effects

✓ JavaScript Features
  - Mobile navigation toggle
  - Smooth scrolling
  - Scroll animations (Intersection Observer)
  - Counter animations for statistics
  - Back-to-top button
  - Parallax effects
  - Active link highlighting

✓ SEO Optimized
  - Semantic HTML5 tags
  - Meta descriptions on all pages
  - Proper heading hierarchy
  - Alt text support (add as needed)
  - Fast loading times

✓ Performance
  - Minimal dependencies (only Google Fonts)
  - Optimized CSS and JavaScript
  - Lazy loading support
  - Efficient animations


═══════════════════════════════════════════════════════════════════════════
7. BROWSER SUPPORT
═══════════════════════════════════════════════════════════════════════════

✅ Chrome (Latest)
✅ Firefox (Latest)
✅ Safari (Latest)
✅ Edge (Latest)
✅ Opera (Latest)
⚠️  IE11 (Partial support - some animations may not work)

Mobile:
✅ iOS Safari (12+)
✅ Chrome Mobile
✅ Samsung Internet
✅ Firefox Mobile


═══════════════════════════════════════════════════════════════════════════
8. DEPLOYMENT
═══════════════════════════════════════════════════════════════════════════

GITHUB PAGES
────────────
1. Create a GitHub repository
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select branch (usually 'main')
5. Click Save
6. Your site will be live at: https://[username].github.io/[repo-name]

NETLIFY
───────
1. Go to netlify.com
2. Drag and drop your project folder
3. Site will be live instantly
4. Custom domain can be added in settings

OTHER HOSTING
─────────────
Simply upload all files to your web hosting provider's public_html or www
folder via FTP or their file manager.


═══════════════════════════════════════════════════════════════════════════
9. SEO OPTIMIZATION TIPS
═══════════════════════════════════════════════════════════════════════════

✓ Add meta descriptions (already included in all pages)
✓ Use proper heading hierarchy (H1 → H2 → H3)
✓ Add alt text to images when you add them
✓ Include keywords naturally in content
✓ Create a sitemap.xml file
✓ Submit to Google Search Console
✓ Ensure fast loading times
✓ Make sure all links work
✓ Use HTTPS when deployed

Current Keywords:
- mumble software
- voice communication
- voice chat
- professional communication


═══════════════════════════════════════════════════════════════════════════
10. TROUBLESHOOTING
═══════════════════════════════════════════════════════════════════════════

PROBLEM: Navigation menu not working on mobile
SOLUTION: Ensure script.js is properly linked at the bottom of HTML files

PROBLEM: Styles not applying
SOLUTION: 
  • Check that style.css is in the same folder as HTML files
  • Clear browser cache (Ctrl+Shift+R or Cmd+Shift+R)
  • Verify CSS file path in HTML

PROBLEM: Links not working
SOLUTION: 
  • Ensure all files are in the same directory
  • Check for typos in href attributes
  • Use relative paths (e.g., "about.html" not "/about.html")

PROBLEM: Animations not smooth
SOLUTION: 
  • Test in different browsers
  • Check if hardware acceleration is enabled
  • Reduce animation complexity if needed

PROBLEM: Google Form button not opening
SOLUTION: 
  • Verify the Google Form URL is correct
  • Check that target="_blank" is present
  • Ensure no JavaScript errors in console


═══════════════════════════════════════════════════════════════════════════
11. CREDITS & LICENSE
═══════════════════════════════════════════════════════════════════════════

Design & Development: Professional Web Solutions
Font: Poppins (Google Fonts)
Icons: SVG icons (custom)
Color Palette: #4361EE, #FFFFFF, #219EBC

This website template is created for Mumble Software.
Feel free to modify and customize according to your needs.


═══════════════════════════════════════════════════════════════════════════
QUICK REFERENCE CARD
═══════════════════════════════════════════════════════════════════════════

Change Colors:        style.css (line 11 - :root section)
Change Text:          Edit respective HTML file
Replace Google Form:  contact.html (search for "docs.google.com")
Replace Download URL: download.html (search for "mumble133.info/download")
Change Navigation:    Edit <nav> section in each HTML file
Modify Footer:        Edit <footer> section in each HTML file


═══════════════════════════════════════════════════════════════════════════

For questions or support, please refer to the official documentation or
contact the development team.

Last Updated: 2024
Version: 1.0

═══════════════════════════════════════════════════════════════════════════
