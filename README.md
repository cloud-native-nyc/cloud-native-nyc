# Cloud Native NYC

Community assets and presentation materials for the Cloud Native NYC chapter.

## Quick Start

### Render the Slides

The presentation (`presentation.html`) is built with [Reveal.js](https://revealjs.com/) loaded from CDN, so no build step is required.

**Option 1 — Open directly in a browser**

Simply double-click `presentation.html` or open it via:
```bash
open presentation.html        # macOS
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

Then navigate to `http://localhost:8000/presentation.html`.

### Slide Navigation

- **Next / Previous**: Right / Left arrow keys  
- **Next / Previous (vertical)**: Down / Up arrow keys  
- **Overview mode**: Press `Esc`  
- **Speaker notes**: Press `S`

## Project Structure

```
cloud-native-nyc/
├── presentation.html       # Reveal.js deck
├── links.html              # Community links page
├── README.md
├── assets/
│   └── images/             # Logos & speaker photos
└── docs/
    └── GOVERNANCE.md       # Community governance draft
```

## Governance

Our governance model is an open-source draft. Read and contribute at:
[docs/GOVERNANCE.md](docs/GOVERNANCE.md)

## Connect

- **Chapter Portal**: https://ocgroups.dev/cncf/group/5pcu8cb  
- **Slack**: `#cloud-native-new-york` on [CNCF Slack](https://slack.cncf.io)  
- **LinkedIn**: https://www.linkedin.com/company/cloud-native-nyc  

---

Hosted by **Scott Rigby** & **Christopher Tineo**
