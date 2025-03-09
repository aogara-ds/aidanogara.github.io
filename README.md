# Aidan O'Gara's Personal Website

This is my personal website, hosted at [aidanogara.com](https://aidanogara.com).

## Technical Details

- Built with Jekyll
- Hosted on GitHub Pages
- Custom design with a professional gray theme and serif fonts

## Development

To run the site locally:

1. Install Jekyll and Bundler:
   ```
   gem install jekyll bundler
   ```

2. Install dependencies:
   ```
   bundle install
   ```

3. Start the development server:
   ```
   bundle exec jekyll serve
   ```

4. Visit `http://localhost:4000` in your browser

## Structure

- `_layouts/`: HTML templates
- `_includes/`: Reusable components
- `_sass/`: Stylesheets
- `_posts/`: Blog posts
- `assets/`: Static files
- `*.md`: Content pages

## Notes for Maintenance

- Add your headshot image to `/assets/images/headshot.jpg`
- Blog posts go in the `_posts` directory with the format `YYYY-MM-DD-title.md`
- Content is written in Markdown

## Custom Domain Setup

The site is configured to be accessible at aidanogara.com through GitHub Pages custom domain feature.