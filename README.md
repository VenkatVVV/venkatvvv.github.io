# Data Science Portfolio Website

A modern, responsive website built with Jekyll to showcase data science projects, blog posts, and visualizations. This website is designed to be hosted on GitHub Pages.

## Features

- 🎯 Clean, modern design
- 📱 Fully responsive layout
- 📊 Project showcase with detailed pages
- 📝 Blog section for articles and tutorials
- 🖼️ Visualization gallery
- 🔍 SEO optimized
- 🚀 Fast loading and performance
- 📈 Easy to maintain and update

## Getting Started

### Prerequisites

- Ruby (version 2.5.0 or higher)
- RubyGems
- Git

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/yourusername.github.io.git
   cd yourusername.github.io
   ```

2. Install dependencies:
   ```bash
   bundle install
   ```

3. Start the local development server:
   ```bash
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser to see the website.

## Project Structure

```
.
├── _config.yml          # Jekyll configuration
├── _layouts/           # HTML layouts
├── _includes/          # Reusable HTML components
├── _posts/            # Blog posts
├── _projects/         # Project pages
├── assets/            # Static assets (CSS, images, etc.)
├── _data/             # Data files (gallery.yml, etc.)
└── index.html         # Homepage
```

## Adding Content

### Projects

1. Create a new file in `_projects/` with the following front matter:
   ```yaml
   ---
   title: Project Title
   description: Project description
   image: /assets/images/project-image.jpg
   tags: [tag1, tag2]
   github: https://github.com/username/repo
   ---
   ```

2. Add your project content below the front matter.

### Blog Posts

1. Create a new file in `_posts/` with the filename format `YYYY-MM-DD-title.md`
2. Add the following front matter:
   ```yaml
   ---
   title: Post Title
   date: YYYY-MM-DD HH:MM:SS +/-TTTT
   categories: [category1, category2]
   tags: [tag1, tag2]
   ---
   ```

### Gallery Items

1. Add your images to `assets/images/gallery/`
2. Update `_data/gallery.yml` with new items:
   ```yaml
   - title: Visualization Title
     description: Description of the visualization
     image: /assets/images/gallery/image.jpg
   ```

## Customization

- Edit `_config.yml` to update site-wide settings
- Modify `_layouts/default.html` to change the site layout
- Update styles in `assets/css/main.css`
- Add your social media links in the footer section of `_layouts/default.html`

## Deployment

This website is designed to be hosted on GitHub Pages. Simply push your changes to the `main` branch, and GitHub Pages will automatically build and deploy your site.

## Contributing

Feel free to submit issues and enhancement requests!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Jekyll for the static site generator
- GitHub Pages for hosting
- All the open-source tools and libraries used in this project 