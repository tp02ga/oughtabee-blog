# OughtaBee Blog - Project Instructions

## Creating New Blog Posts

When asked to create a blog post for this Jekyll site:

1. **File location:** `_posts/` folder
2. **File naming format:** `YYYY-MM-DD-post-title-with-dashes.md`
   - Example: `2026-02-15-how-to-automate-your-content.md`

3. **Required front matter** (must be at the top of every post):

```yaml
---
title: "Your Post Title Here"
date: 2026-02-15
author: Trevor Page
description: "A compelling 150-160 character description for search engines."
image: /assets/images/your-image.jpg
---
```

4. **Then add the post content** in Markdown format below the front matter.

### Front Matter Fields

- `title` - Shows in browser tab and search results
- `date` - Publication date (should match filename date)
- `author` - Post author (default: Trevor Page)
- `description` - Meta description for Google (150-160 chars)
- `image` - Used for social sharing (Open Graph)
