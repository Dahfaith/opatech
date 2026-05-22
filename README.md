# Opatech Photography Int'L

A premium modern photography company website designed for a luxury wedding brand in the UK and Nigeria.

## Tech Stack
- HTML5
- Tailwind CSS (via CDN)
- Vanilla JavaScript
- FontAwesome Icons
- Google Fonts (Inter & Playfair Display)

## Features
- **Mobile-first & Responsive**: Scales elegantly from phones to large desktop monitors.
- **Cinematic Aesthetic**: Deep Red (`#b30000`) and Soft Gold (`#d4af37`) accents on a dark/light theme to convey a luxurious feel.
- **Interactive Gallery**: Masonry layout with custom filtering and a built-in lightweight Lightbox for image previews.
- **Scroll Animations**: Smooth fade-in effects on scroll utilizing the Intersection Observer API.
- **Dynamic Counters**: Animated stat counters that trigger upon scrolling into view.
- **Zero Build Tools**: Uses the Tailwind Play CDN to allow for immediate deployment to platforms like GitHub Pages without the need for CI/CD pipelines or `npm` build steps.

## Directory Structure
```
/
|-- index.html           # Main homepage with 11 sections
|-- /assets
    |-- /css
        |-- main.css     # Custom animations and scroll styles
    |-- /js
        |-- script.js    # Logic for navbar, mobile menu, lightbox, and filters
    |-- /images          # (For local image assets)
    |-- /videos          # (For local video assets)
```

## How to Deploy
1. Since there are no build tools required, you can directly push this repository to GitHub.
2. Go to your repository settings -> **Pages**.
3. Select the `main` branch (or `master`) and hit Save.
4. Your luxury website is now live!
