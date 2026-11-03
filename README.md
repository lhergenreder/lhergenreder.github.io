# Luciano Hergenreder - Academic Website

Personal academic website and portfolio of Luciano Hergenreder, PhD Candidate in Fluid Mechanics at Pontificia Universidad Católica de Chile.

Based on the [Academic Jekyll Theme](https://github.com/LeNPaul/academic) adapted with a clean, focused layout.

## Structure

```
├── _config.yml               # Site configuration (title, URL, baseurl)
├── _data/
│   ├── settings.yml          # Navigation menu and social links
│   ├── news.yml              # News and recent updates
│   ├── publications.yml      # Publications and abstracts
│   └── research.yml          # Research setups and facilities
├── _includes/                # Header, footer, head, contact, publications
├── _layouts/                 # Default, home, research, publications, contact, updates
├── _sass/                    # SCSS styles and theme customization
├── assets/
│   ├── img/                  # Images and video media
│   └── libs/                 # Bootstrap & FontAwesome
├── index.md                  # Home / About page
├── research.md               # Research facilities page
├── publications.md           # Publications page
├── contact.md                # Contact details
└── updates.md                # Updates archive
```

## Running Locally

To build and preview locally with Jekyll:

```bash
bundle install
bundle exec jekyll serve
```

Then navigate to `http://localhost:4000/`.

## Publishing to GitHub Pages

1. Create a public repository named `lhergenreder.github.io` on GitHub under your account `lhergenreder`.
2. Connect your local repository and push:
   ```bash
   git remote add origin https://github.com/lhergenreder/lhergenreder.github.io.git
   git branch -M main
   git push -u origin main
   ```
3. In GitHub: go to **Settings > Pages** and select `Deploy from a branch` (Branch: `main`, Folder: `/ (root)`).
