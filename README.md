# Polly Yao — Personal Website

Personal academic website built with Jekyll, for job search, PhD applications, and project portfolio.

## Prerequisites

- Ruby (recommended: 3.x)
- Bundler

Install Bundler if you don't have it:

```bash
gem install bundler
```

## Run Locally

1. Clone the repository:

```bash
git clone https://github.com/Pollyyaooo/Pollyyaooo.github.io.git
cd Pollyyaooo.github.io
```

2. Install dependencies:

```bash
bundle install
```

3. Start the local server:

```bash
bundle exec jekyll serve
```

4. Open your browser and go to `http://localhost:4000`

## Project Structure

```
├── _includes/       # Reusable HTML components (navigation, footer, etc.)
├── _layouts/        # Page layout templates
├── _pages/          # Static pages (projects list, 404)
├── _posts/          # Blog posts (Markdown)
├── _projects/       # Project detail pages (Markdown)
├── assets/          # CSS, images, fonts, PDF (CV)
├── _config.yml      # Site configuration
└── index.md         # Homepage content
```

## Customization

- **Personal info**: Edit `_config.yml` (name, description, social links)
- **Homepage**: Edit `index.md`
- **Add a project**: Create a new `.md` file in `_projects/`
- **Add a blog post**: Create a new `.md` file in `_posts/` with filename format `YYYY-MM-DD-title.md`
- **CV**: Replace `assets/pdf/Polly_Yao_CV.pdf`
