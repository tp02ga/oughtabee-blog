# OughtaBee Blog

The official blog for [OughtaBee AI](https://oughtabee.ai), built with Jekyll and hosted on GitHub Pages.

**Live site:** [blog.oughtabee.ai](https://blog.oughtabee.ai)

## Creating a New Blog Post

1. Add a new Markdown file in `_posts/` with the naming format:

   ```
   YYYY-MM-DD-your-post-title-with-dashes.md
   ```

2. Include the required front matter at the top:

   ```yaml
   ---
   title: "Your Post Title Here"
   date: 2026-02-15
   author: Trevor Page
   description: "A compelling 150-160 character description for search engines."
   image: /assets/images/your-image.jpg
   permalink: /your-custom-url-slug/
   ---
   ```

3. Write your post content in Markdown below the front matter.

### Front Matter Fields

| Field | Required | Description |
|-------|----------|-------------|
| `title` | Yes | Shows in browser tab, search results, and social sharing |
| `date` | Yes | Publication date (should match the filename date) |
| `author` | Yes | Post author name |
| `description` | Yes | Meta description for SEO (aim for 150-160 characters) |
| `image` | No | Featured image path — displays on the homepage and at the top of the article |
| `permalink` | No | Custom URL slug (defaults to `/:title/`) |

### Adding a Featured Image

1. Place the image in `assets/images/`
2. Set the `image` field in front matter to its path (e.g. `/assets/images/my-image.jpg`)
3. The image will automatically appear:
   - On the **homepage** if the post is the most recent (featured article)
   - At the **top of the article** page itself

## Project Structure

```
_posts/           → Blog post Markdown files
_layouts/         → Page templates (default.html, post.html)
_includes/        → Reusable HTML partials (head.html)
assets/css/       → Stylesheets
assets/images/    → Post images and site assets
index.html        → Blog homepage
_config.yml       → Jekyll site configuration
```

## Deployment

Pushing to `main` automatically deploys to GitHub Pages.
