# Kith - Coordinate Help With People You Trust

A website for Kith, a platform that helps families coordinate mutual aid through trusted circles.

## Overview

Kith enables 8-15 trusted people to coordinate help exchanges using time credits. Free circle coordination + vetted provider network backup.

**Key Features:**
- 6 help types: Childcare, Rides, Skills, Projects, Meals, More
- Time credit system (1 hour = 1 credit)
- Provider network when circle can't help
- Lifecycle retention (circles grow with you)
- Privacy-first, zero-knowledge encryption

## Pages

1. **index.html** - Homepage with 6 help types, examples, comparisons
2. **why.html** - Philosophy, research, lifecycle retention
3. **how.html** - Detailed flows for different exchange types
4. **faq.html** - Updated Q&A addressing multi-use and provider network
5. **contact.html** - Contact information
6. **privacy.html** - Zero-knowledge encryption policy
7. **paid-services.html** - Provider network details
8. **revenue.html** - Transparent pricing model
9. **alternatives.html** - Competitor comparisons

## Navigation

All pages use consistent navigation:
```
Home | Why | How It Works | FAQ | Contact
```

## Design

- **Colors:** Sage green (#7A9B76), Clay/Terracotta (#C95D3D), Warm white (#FFFEF9)
- **Fonts:** Fraunces (headings), DM Sans (body)
- **Logo:** Olympicos 5-ring design (SVG inline on all pages)
- **Responsive:** Mobile-first design with breakpoints

## Running Locally

Simply open any HTML file in a web browser:

```bash
open index.html
```

Or use a local server:

```bash
# Python 3
python3 -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000

# Node.js (http-server)
npx http-server

# VS Code Live Server
# Install "Live Server" extension and right-click index.html > Open with Live Server
```

Then visit: http://localhost:8000

## Project Structure

```
kith-website/
├── index.html              # Homepage
├── why.html               # Philosophy
├── how.html               # How it works
├── faq.html               # FAQ
├── contact.html           # Contact
├── privacy.html           # Privacy policy
├── paid-services.html     # Provider network
├── revenue.html           # Pricing
├── alternatives.html      # Competitor comparison
└── README.md             # This file
```

## Key Messaging

**Not:** "Babysitter app" or "Starting with childcare"
**Instead:** "Coordinate help with people you trust. Automatically fair."

- Same 8-15 people for multiple help types
- Provider network integrated (not buried)
- Lifecycle retention (circles grow with you)
- Fair tracking built-in (time credits)

## Built By

Small team in Richmond, VA and Washington, DC  
Building infrastructure for regenerative family networks

## License

Copyright © 2026 The Village (Kith)
All rights reserved.
