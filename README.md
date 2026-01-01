# NEON ONSLAUGHT - Installation Instructions

## For iPhone/iPad (iOS):

### Option 1: Add to Home Screen (Recommended)
1. Upload all files to a web server or use a free hosting service like:
   - GitHub Pages (free, easy)
   - Netlify (free)
   - Vercel (free)

2. Open the game URL in Safari on your iPhone

3. Tap the Share button (square with arrow pointing up)

4. Scroll down and tap "Add to Home Screen"

5. Tap "Add" in the top right corner

6. The game will now appear as an app icon on your home screen!

### Option 2: Use GitHub Pages (Free Hosting)
1. Create a GitHub account (if you don't have one)
2. Create a new repository called "neon-onslaught"
3. Upload all these files:
   - index.html
   - manifest.json
   - sw.js
   - icon-192.png
   - icon-512.png
4. Go to Settings → Pages
5. Select "main" branch as source
6. Your game will be live at: https://YOUR-USERNAME.github.io/neon-onslaught/

### Option 3: Local Testing
For quick testing on iPhone without hosting:
1. Open index.html in Safari (it should work directly in the browser)
2. For best experience, use full-screen mode

## Files Included:
- **index.html** - Main game file
- **manifest.json** - PWA configuration
- **sw.js** - Service worker for offline play
- **icon-192.png** - App icon (small)
- **icon-512.png** - App icon (large)

## Why PWA?
Progressive Web Apps (PWAs) can be installed on your iPhone home screen and run like native apps:
- No App Store required
- Works offline after first load
- Full-screen experience
- Looks and feels like a real app

## Troubleshooting:
- **Game displays as text/code**: Make sure you're opening index.html in Safari browser
- **Can't add to home screen**: Must be served over HTTPS (use GitHub Pages or other hosting)
- **Touch controls not working**: Refresh the page and make sure you're touching the joystick/fire button areas
