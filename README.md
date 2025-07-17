# Academic Portfolio - GitHub Pages with Jekyll

This repository contains a GitHub Pages website built with Jekyll using the Mediumish theme. It's designed to showcase academic work, research, and publications.

## Features

- Responsive design using the Mediumish theme
- Blog functionality for sharing research and updates
- Support for featured posts
- Easy customization through _config.yml

## Local Development

To run this site locally:

1. Make sure you have Ruby installed (version 2.5.0 or higher)
2. Install Bundler if you don't have it:
   ```
   gem install bundler
   ```
3. Clone this repository:
   ```
   git clone https://github.com/sjwalton/sjwalton.github.io.git
   cd sjwalton.github.io
   ```
4. Install dependencies:
   ```
   bundle install
   ```
5. Start the local server:
   ```
   bundle exec jekyll serve
   ```
6. View the site at [http://localhost:4000](http://localhost:4000)

## Adding Content

### Blog Posts

To add a new blog post:

1. Create a new file in the `_posts` directory with the format `YYYY-MM-DD-title.md`
2. Add front matter at the top of the file:
   ```yaml
   ---
   layout: post
   title: "Your Post Title"
   author: sjwalton
   categories: [Category1, Category2]
   image: assets/images/your-image.jpg
   featured: true  # Set to true to feature this post
   hidden: false   # Set to true to hide from the main page
   ---
   ```
3. Write your content below the front matter using Markdown

### Images

Place all images in the `assets/images` directory and reference them in your posts using:
```
![Alt text](/assets/images/your-image.jpg)
```

## Customization

### Site Configuration

Edit `_config.yml` to change site settings:

- Site title, description, and metadata
- Social media links
- Author information
- Theme settings

### Theme

This site uses the Mediumish theme. You can customize the theme by:

1. Creating or modifying files in the `_layouts` and `_includes` directories
2. Adding custom CSS in `assets/css/custom.css`

## Deployment

This site is automatically deployed to GitHub Pages when changes are pushed to the main branch. No additional setup is required.

## Required Image Files

The following image files need to be added to the `assets/images` directory:

- `logo.png` - Site logo (recommended size: 300x80px)
- `favicon.ico` - Site favicon (recommended size: 32x32px)
- `avatar.png` - Author avatar (recommended size: 200x200px)
- `welcome-post.jpg` - Featured image for the welcome post (recommended size: 1200x600px)

## Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Mediumish Theme Documentation](https://github.com/wowthemesnet/mediumish-theme-jekyll)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)