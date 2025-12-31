# Development & Deployment

This directory contains configuration for Protocol Zero's documentation site and CI/CD pipelines.

## Contents

- **`mkdocs.yml`** - MkDocs configuration for documentation site
- **`workflows/`** - GitHub Actions workflows
  - `deploy-docs.yml` - Auto-deploy to GitHub Pages on push to main

## Local Development

### Prerequisites

- Python 3.8+
- pip

### Setup

```bash
# Install dependencies
pip install -r .github/requirements.txt

# Serve locally
cd .github
mkdocs serve

# Open browser to http://127.0.0.1:8000
```

### Build

```bash
cd .github
mkdocs build

# Output will be in .github/site/
```

## GitHub Pages Deployment

Documentation can be deployed to GitHub Pages when changes are pushed to `main` branch (enable Pages in repo settings and set `site_url` in `mkdocs.yml` when live).

### Manual Deployment

```bash
cd .github
mkdocs gh-deploy --force
```

## 🎨 Theme Features

- **Material for MkDocs** - Modern, responsive design
- **Light/Dark mode** - Automatic based on system preference
- **Multi-language support** - 8 languages (English is complete, others coming soon)
- **Search** - Full-text search across all documentation
- **Navigation** - Organized by Parts and Appendices
- **Mobile-friendly** - Responsive design for all devices

## 🔧 Configuration

### Adding a New Language

1. Create folder in `protocol/[lang-code]/`
2. Copy structure from `protocol/en/`
3. Translate content
4. Update `mkdocs.yml`:
   ```yaml
   extra:
     alternate:
       - name: Your Language
         link: /your-lang/
         lang: your-lang
   ```
5. Update i18n plugin settings

### Customizing Theme

Edit `.github/mkdocs.yml`:
- **Colors:** `theme.palette.primary` and `theme.palette.accent`
- **Features:** `theme.features` array
- **Plugins:** `plugins` section

## 📊 Analytics (Optional)

To add Google Analytics:

```yaml
extra:
  analytics:
    provider: google
    property: G-XXXXXXXXXX
```

## 🐛 Troubleshooting

**Build fails:**
- Check `requirements.txt` versions
- Ensure all markdown files exist
- Validate `mkdocs.yml` syntax

**Pages not updating:**
- Check GitHub Actions tab for errors
- Ensure GitHub Pages is enabled in repo settings
- Verify Pages source is set to "GitHub Actions"

**Local serve not working:**
- Run from `.github/` directory
- Check Python and pip versions
- Clear cache: `rm -rf ~/.cache/pip`

---

For more info: https://squidfunk.github.io/mkdocs-material/
