# PakSec Nation – USB Attack Concepts Workshop

Landing page for the 2-hour educational & defensive workshop.

## Deploy to Netlify

1. Push this folder to a GitHub repository.
2. In [Netlify](https://app.netlify.com): **Add new site → Import from Git**.
3. Select the repo. Build settings:
   - **Publish directory:** `/` (root of this folder)
   - **Build command:** leave empty (static HTML)
4. Deploy. Your site will be live at `*.netlify.app`.

## Local preview

Open `index.html` in a browser, or:

```bash
npx serve .
```

## Structure

```
paksec-workshop-site/
├── index.html          # Main landing page
├── assets/
│   └── paksec-logo.png # PakSec Nation logo
└── README.md
```

## Links

- Main site: https://paksec-nation.netlify.app
- PECA PDF: https://sja.gos.pk/assets/Updated_Laws/The%20Prevention%20of%20Electronic%20Crimes%20Act,%20Rules%20Final%20Index%20(%20Upto%20date%202025).pdf
- NCCIA Laws: https://www.nccia.gov.pk/laws.php
