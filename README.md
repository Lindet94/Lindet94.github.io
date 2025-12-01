# Lindet94.github.io

> Personal website and technical blog of Erik Lindmaa - Cloud Engineer

## Overview

This is my personal website built with [Jekyll](https://jekyllrb.com/) and the [Minima theme](https://github.com/jekyll/minima). It serves as a hub for my technical write-ups, notes, and professional information.

## Features

- **Blog**: Technical posts about cloud engineering, Azure, Python, and DevOps
- **Resume**: Professional background and experience
- **Contact**: Ways to get in touch
- **Responsive Design**: Works on desktop and mobile devices
- **Dark/Light Mode**: Automatic theme switching based on system preferences

## Tech Stack

- **Jekyll**: Static site generator
- **Minima Theme**: Clean, minimal Jekyll theme
- **Markdown**: Content authoring
- **GitHub Pages**: Hosting platform

## Local Development

### Prerequisites

- Ruby 2.7+
- Bundler gem

### Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/Lindet94/Lindet94.github.io.git
   cd Lindet94.github.io
   ```

2. Install dependencies:

   ```bash
   bundle install
   ```

3. Start the local server:

   ```bash
   bundle exec jekyll serve
   ```

4. Open your browser to `http://localhost:4000`

### Adding New Content

- **Blog Posts**: Add markdown files to the `posts/` directory with Jekyll front matter
- **Pages**: Create markdown files in the root directory and add them to `header_pages` in `_config.yml`
- **Assets**: Place images, CSS, and JavaScript in the `assets/` directory

## Project Structure

```
Lindet94.github.io/
├── _config.yml          # Jekyll configuration
├── _includes/           # Reusable includes
├── assets/              # CSS, JS, images
├── posts/               # Blog posts
├── blog.md              # Blog index page
├── contact.md           # Contact information
├── index.md             # Homepage
├── resume.md            # Professional resume
└── README.md            # This file
```

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. No additional deployment configuration is needed.

## License

This project is open source and available under the [MIT License](LICENSE).

## Contact

- **Email**: erik.lindmaa@gmail.com
- **GitHub**: [@Lindet94](https://github.com/Lindet94)
- **LinkedIn**: [Erik Lindmaa](https://linkedin.com/in/erik-lindmaa-8761b1116)
