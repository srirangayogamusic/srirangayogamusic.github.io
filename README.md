# Sri Ranga Yoga & Music Website

A professional, responsive single-page website for **Sri Ranga Yoga & Music**, run by
YCB Certified Yoga Trainer **V.S. Anil** (Ministry of AYUSH, Govt. of India).

## Features
- Modern, mobile-first responsive design
- Sections: Hero, About, Yoga & Wellness, Carnatic Music, Schedule & Fees, Contact
- Animated stats counters and scroll reveals
- Click-to-WhatsApp and click-to-call buttons (+91 70229 12656)
- Floating WhatsApp button
- No build step, just plain HTML / CSS / vanilla JS

## Project structure
```
.
├── index.html        # Page markup
├── css/style.css     # Styles & responsive layout
├── js/script.js      # Navbar, mobile menu, reveals, counters
└── assets/           # (Optional) place your own photos here
```

## Run locally
Just open `index.html` in a browser, or serve it:
```bash
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Customise
- **Phone number / WhatsApp:** search for `7022912656` in `index.html` and replace.
- **Photos:** the hero, about and music images currently use Unsplash placeholders
  (the `background:` URLs in `css/style.css`). Replace them with your own photos:
  drop files in `assets/` and update the URLs in `css/style.css`.
- **Colours:** edit the CSS variables at the top of `css/style.css` (`:root`).
- **Text/content:** all copy lives in `index.html`.

## Deploy (free options)
- **Netlify / Vercel:** drag-and-drop the folder, or connect this repo.
- **GitHub Pages:** push to GitHub → Settings → Pages → deploy from `main` branch.

---
Trainer: **V.S. Anil** · 📞 +91 70229 12656
