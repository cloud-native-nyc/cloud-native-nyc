# Presentation: Building the Community Bridge in Cloud Native NYC Chapter

Code for Roundtable Discussion by hosted by **Scott Rigby** & **Christopher Tineo**, At KCD New York 2026.

## Roundtable Description

There’s no single path into the cloud native community—and it doesn’t have to start with code.

Join maintainers and community leaders to talk about how to get involved, whether through contributions, events, documentation, or storytelling. Bring your questions, ideas, or curiosity and find your place in the ecosystem.

## Pages

- [presentation.html](presentation.html)
- [links.html](links.html)

## Run Locally

### Serve

The presentation (`presentation.html`) is built with [Reveal.js](https://revealjs.com/) loaded from CDN, so no build step is required.

**Option 1 — Open directly in a browser**

Simply double-click `presentation.html` or open it via:

```bash
open presentation.html      # macOS
xdg-open presentation.html  # Linux
```

**Option 2 — Serve via a local HTTP server (recommended)**

For the best experience (fonts, transitions, and speaker notes):

```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve .
```

Then open <http://localhost:8000/presentation.html>

### Navigate

- **Next / Previous**: Right / Left arrow keys  
- **Next / Previous (vertical)**: Down / Up arrow keys  
- **Overview mode**: Press `Esc`  
- **Speaker notes**: Press `S`
