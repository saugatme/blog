# Saugat’s Blog

Independent blog at https://saugatme.github.io/blog/ using GitHub Pages and Jekyll. No JavaScript, third-party fonts, tracking, or build dependencies to maintain yourself. The theme follows the reader’s system light/dark setting.

## Publish a post (in your browser)
1. Open this repository on GitHub. Open `post-template.md` and copy its contents.
2. Choose **Add file → Create new file**.
3. Name it `_posts/YYYY-MM-DD-your-post-title.md` (for example `_posts/2026-11-09-a-new-note.md`).
4. Paste the template. Change the title, description and category (`Personal`, `Professional`, or anything suitable). Write below the second `---`.
5. Use GitHub’s **Preview** tab to check formatting. Commit to `main` when ready. GitHub Pages publishes automatically, usually within a few minutes.

## Drafts
Keep unpublished writing outside the public repository for privacy. For a public work-in-progress, use `_drafts/your-title.md`; Jekyll does not publish it, but the file remains visible on GitHub. Never put private writing or patient data here. Future-dated posts are excluded until a later site build; this is not automatic scheduling.

## Images
Upload to `assets/images/`, then write `![A useful description]({{ '/assets/images/filename.jpg' | relative_url }})`. Resize large images before uploading. Only publish material you have permission to share.

## Editing and maintenance
- Homepage: `index.html`
- Layout and navigation: `_layouts/default.html`
- Article layout: `_layouts/post.html`
- Colors and typography: `assets/blog.css`
- Site address: `_config.yml` (keep `baseurl: /blog`)
- Welcome post: `_posts/2026-11-08-a-place-for-notes.md` — edit or remove whenever you wish.

The portfolio’s root robots.txt currently asks crawlers to avoid all paths, including `/blog/`. This is voluntary and does not make posts private. No separate analytics are installed.
