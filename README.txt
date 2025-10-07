================================================================================
                        IDLEMASTER WEBSITE - README
================================================================================

Welcome to the IdleMaster website! This is a professional, modern, responsive
multi-page website built with HTML, CSS, and JavaScript.

================================================================================
TABLE OF CONTENTS
================================================================================

1. Quick Start Guide
2. File Structure
3. How to Run the Website Locally
4. Customization Guide
   - Changing Colors
   - Updating Links
   - Modifying Text Content
   - Replacing Keywords
5. Technical Details
6. Browser Compatibility
7. Troubleshooting
8. Credits

================================================================================
1. QUICK START GUIDE
================================================================================

To run the website:
1. Open the folder containing all website files
2. Double-click on "index.html" to open in your default browser
3. Navigate through the site using the navigation menu

That's it! No server or installation required.

================================================================================
2. FILE STRUCTURE
================================================================================

IdleMaster4/
│
├── index.html          # Home page
├── about.html          # About page
├── contact.html        # Contact page
├── download.html       # Download page
├── style.css           # Main stylesheet
├── script.js           # JavaScript functionality
└── README.txt          # This file

================================================================================
3. HOW TO RUN THE WEBSITE LOCALLY
================================================================================

METHOD 1: Direct Browser Open
------------------------------
1. Navigate to the website folder
2. Double-click "index.html"
3. The website will open in your default browser

METHOD 2: Using Live Server (Recommended for Development)
----------------------------------------------------------
If you're using Visual Studio Code:
1. Install the "Live Server" extension
2. Right-click on "index.html"
3. Select "Open with Live Server"
4. The website will open with live reload functionality

METHOD 3: Python HTTP Server
-----------------------------
If you have Python installed:
1. Open terminal/command prompt in the website folder
2. Run: python -m http.server 8000
3. Open browser and go to: http://localhost:8000

================================================================================
4. CUSTOMIZATION GUIDE
================================================================================

4.1 CHANGING COLORS
-------------------
Open "style.css" and find the CSS Variables section (lines 1-15):

:root {
    --primary-color: #D10000;      /* Main red color */
    --secondary-color: #FFFFFF;    /* White */
    --accent-color: #D10000;       /* Accent red */
    --bg-light: #EFEFEF;          /* Light gray background */
    --bg-white: #FFFFFF;          /* White background */
    --text-dark: #2C2C2C;         /* Dark text */
    --text-gray: #666666;         /* Gray text */
    --text-light: #999999;        /* Light gray text */
}

Simply change these hex color codes to your preferred colors.
The changes will automatically apply to the entire website.

Example:
- To change the primary color from red to blue:
  Change --primary-color: #D10000; to --primary-color: #0066FF;

4.2 UPDATING LINKS
------------------

GOOGLE FORM LINK (Contact Page)
--------------------------------
File: contact.html
Find (around line 77): 
<a href="https://docs.google.com/forms/d/e/1FAIpQLSfXccBSTtUKYMICf3NnmZpUrl8_CD2NmDD1Chn2ACITgjXihQ/viewform?usp=header"

Replace the URL with your own Google Form link.

GITHUB REPOSITORY LINK
-----------------------
Update in ALL pages (index.html, about.html, contact.html, download.html):
Find: https://github.com/subtitle-edit/Idle-Master
Replace with your GitHub repository URL

DOWNLOAD PAGE LINK
------------------
File: download.html
Find (around line 73):
<a href="https://idlemaster.net/download/">

Replace with your actual download URL.

OFFICIAL WEBSITE LINK
---------------------
File: index.html (and other pages in footer)
Find: https://idlemaster.net/
Replace with your official website URL.

4.3 MODIFYING TEXT CONTENT
---------------------------

HOME PAGE (index.html)
----------------------
- Hero Title: Line 51 - Change "Welcome to IdleMaster"
- Hero Subtitle: Line 52 - Change subtitle text
- Hero Description: Line 53 - Update description
- Features: Lines 75-117 - Modify feature cards
- About Preview: Lines 126-132 - Update about text
- Statistics: Lines 136-148 - Change numbers and labels

ABOUT PAGE (about.html)
-----------------------
- Mission: Lines 55-60 - Update mission statement
- Vision: Lines 63-68 - Update vision statement
- Core Values: Lines 75-96 - Modify values
- Story: Lines 102-109 - Change your story
- Statistics: Lines 121-136 - Update team statistics

CONTACT PAGE (contact.html)
---------------------------
- Intro Text: Lines 51-53 - Change introduction
- Contact Info Cards: Lines 81-103 - Update contact methods
- FAQ Section: Lines 109-130 - Modify FAQ items

DOWNLOAD PAGE (download.html)
-----------------------------
- Version Info: Lines 62-72 - Update platform, license, size
- System Requirements: Lines 83-108 - Modify requirements
- Installation Steps: Lines 118-147 - Change installation guide
- Features List: Lines 154-179 - Update feature list

4.4 REPLACING KEYWORDS
----------------------

The website uses "IdleMaster" and "idlemaster" as primary keywords.
To change keywords:

1. Use Find & Replace in your text editor
2. Search for: "IdleMaster" or "idlemaster"
3. Replace with: Your desired keyword
4. Make sure to do this in ALL HTML files

Note: Be careful with case sensitivity. "IdleMaster" appears in:
- Navigation logo
- Page titles
- Meta descriptions
- Content text

================================================================================
5. TECHNICAL DETAILS
================================================================================

TECHNOLOGIES USED
-----------------
- HTML5 (Semantic markup)
- CSS3 (Flexbox, Grid, Custom Properties, Animations)
- JavaScript (ES6+)
- Google Fonts (Poppins)

FEATURES
--------
- Fully Responsive Design (Mobile, Tablet, Desktop)
- Mobile Navigation Menu (Hamburger)
- Smooth Scroll Animations
- Scroll-to-Top Button
- Intersection Observer for animations
- SEO-Friendly Structure
- Cross-browser Compatible
- Fast Loading Performance

CSS FEATURES
------------
- CSS Custom Properties (Variables)
- CSS Grid for Layouts
- Flexbox for Alignment
- Smooth Transitions
- Hover Effects
- Keyframe Animations

JAVASCRIPT FEATURES
-------------------
- Mobile Menu Toggle
- Smooth Scrolling
- Scroll Animations
- Active Page Highlighting
- Scroll-to-Top Button
- Performance Optimization (Debouncing)

================================================================================
6. BROWSER COMPATIBILITY
================================================================================

The website is compatible with:

✓ Google Chrome (Latest)
✓ Mozilla Firefox (Latest)
✓ Safari (Latest)
✓ Microsoft Edge (Latest)
✓ Opera (Latest)

Mobile Browsers:
✓ Chrome Mobile
✓ Safari iOS
✓ Samsung Internet
✓ Firefox Mobile

Minimum Requirements:
- JavaScript must be enabled
- CSS3 support required
- Modern browser (released after 2018)

================================================================================
7. TROUBLESHOOTING
================================================================================

PROBLEM: Styles not loading
SOLUTION: Make sure "style.css" is in the same folder as HTML files

PROBLEM: Navigation menu not working on mobile
SOLUTION: Ensure "script.js" is in the same folder and JavaScript is enabled

PROBLEM: Links not working
SOLUTION: Check that all href attributes contain correct URLs

PROBLEM: Images not loading (if you add images)
SOLUTION: Verify image paths are correct and images are in the right folder

PROBLEM: Google Form button not opening
SOLUTION: Check that the Google Form URL is correct and accessible

PROBLEM: Website looks broken on mobile
SOLUTION: Clear browser cache and ensure viewport meta tag is present

PROBLEM: Animations not working
SOLUTION: Check if IntersectionObserver is supported in your browser

================================================================================
8. CREDITS
================================================================================

Design Inspiration: https://idlemaster.net/
Designed & Developed by: Factory Droid
Font: Poppins (Google Fonts)
Icons: SVG icons (inline)

================================================================================

COLOR PALETTE REFERENCE
=======================
Primary Color:   #D10000 (Red)
Secondary Color: #FFFFFF (White)
Accent Color:    #D10000 (Red)
Background:      #EFEFEF (Light Gray)

================================================================================

SOCIAL MEDIA & LINKS
====================
Official Website: https://idlemaster.net/
GitHub: https://github.com/subtitle-edit/Idle-Master
Download: https://idlemaster.net/download/
Contact Form: [Your Google Form URL]

================================================================================

MAINTENANCE TIPS
================

1. Regularly update content to keep it fresh
2. Test the website on different devices and browsers
3. Optimize images before adding them to reduce file size
4. Keep backups of your customized files
5. Test all links periodically to ensure they're working
6. Update copyright year in footer annually
7. Consider adding analytics (Google Analytics) for tracking

================================================================================

DEPLOYMENT OPTIONS
==================

OPTION 1: GitHub Pages (Free)
------------------------------
1. Create a GitHub repository
2. Upload all website files
3. Go to repository Settings > Pages
4. Select main branch as source
5. Your site will be live at: username.github.io/repository-name

OPTION 2: Netlify (Free)
-------------------------
1. Go to netlify.com
2. Drag and drop your website folder
3. Site will be live instantly with custom URL

OPTION 3: Traditional Web Hosting
----------------------------------
1. Purchase hosting and domain
2. Upload files via FTP/cPanel File Manager
3. Access your site at your domain name

================================================================================

NEED MORE HELP?
===============

If you need additional customization or have questions:
1. Check the code comments in each file
2. Refer to this README
3. Search for specific HTML/CSS/JavaScript tutorials online
4. Contact support through the contact form

================================================================================

VERSION INFORMATION
===================
Website Version: 1.0
Created: 2024
Last Updated: 2024

================================================================================

Thank you for using the IdleMaster website template!

For more information, visit: https://idlemaster.net/

================================================================================
                            END OF README
================================================================================
