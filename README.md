# CT-101 Portfolio: Manufactured Judgment

Interactive portfolio for CT-101: Persuasion and Resistance (Fall 2025)

## Overview

This portfolio examines how visual rhetoric, psychological archetypes, and algorithmic systems manufacture judgment at scale. Three studies trace a common pattern: designed systems that shape public perception and individual behavior in ways that resist correction by evidence alone.

### Contents

1. **Depth Study**: Anne Lund vs. Generation Atomic - Visual rhetoric of nuclear fear
2. **Persona/Archetype**: The Concerned Parent - Manufactured psychological archetype
3. **Practice of Embodiment**: The Noob - Interactive flowchart for navigating algorithmic judgment in gaming

## Development

```bash
# Install dependencies
npm install

# Start dev server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview
```

## Deployment to GitHub Pages

1. Create a new GitHub repository
2. Update `astro.config.mjs` with your GitHub username:
   ```js
   export default defineConfig({
     site: 'https://YOUR-USERNAME.github.io',
     base: '/ct101-portfolio',
   });
   ```
3. Push to GitHub
4. Go to repository Settings > Pages
5. Under "Build and deployment", select "GitHub Actions"
6. The site will deploy automatically on push to `main`

## Tech Stack

- [Astro](https://astro.build/) - Static site generator
- Vanilla JavaScript - Interactive flowchart
- CSS - Custom styling

## Credits

Created by Brandon Figarella for CT-101: Persuasion and Resistance
Instructor: Dr. Dorothy R. Santos
UC Santa Cruz, Fall 2025
