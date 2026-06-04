# Madagascar Educational Opportunities

A website for **Madagascar Educational Opportunities (MAD)**, a nonprofit making high
school education accessible to bright, hard-working students from rural Madagascar —
where many villages have no high school of their own. The site shares the students'
stories, explains how the sponsorship program works, and invites visitors to donate.

## About the site

This is a static website (plain HTML, CSS, and JavaScript — no build step or server
required). Visitors can learn about the challenge facing rural students, see the
program's impact, read student stories, and make a donation.

## Project structure

```
mad-opportunities/
├── index.html      # The main (single-page) site
├── css/            # Stylesheets
├── js/             # JavaScript
├── images/         # Photos and graphics
└── reports/        # Supporting documents / reports
```

## Viewing it locally

Because it's a static site, you can simply open `index.html` in your web browser.

If you'd prefer to run it through a local web server (so things like fonts and images
load exactly as they would online), you can use Python's built-in server:

```bash
# From inside the mad-opportunities folder:
python -m http.server 8000
```

Then visit <http://localhost:8000> in your browser.

## License

© Madagascar Educational Opportunities. All rights reserved. See [LICENSE](LICENSE).
