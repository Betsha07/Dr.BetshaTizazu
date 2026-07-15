# Dr. Betsha Tizazu Abreham Personal Website

This is a ready-to-use one-page academic website for Dr. Betsha Tizazu Abreham.

## Files

- `index.html` — main website content
- `styles.css` — visual design and responsive layout
- `script.js` — mobile menu and footer year

## How to edit

1. Replace the `BT` placeholder in the hero card with a professional photo.
2. Update the publications section with the full and exact Google Scholar list.
3. Add DOI links where available.
4. Add a downloadable CV file and link it to the hero button if needed.
5. Replace or remove any project sections that are not relevant.

## How to publish online

### Option 1: GitHub Pages
1. Create a new GitHub repository.
2. Upload these files.
3. Go to Settings → Pages.
4. Select the main branch and root folder.
5. Publish.

### Option 2: Netlify
1. Go to Netlify.
2. Drag and drop this folder.
3. Netlify will publish the website instantly.

### Option 3: cPanel / hosting
1. Upload all files to `public_html`.
2. Open the domain name to view the site.

## Suggested domain

- `betshatizazu.com`
- `drbetshatizazu.com`


## Updating News and Blog

Open `index.html` and search for:

- `EDIT NEWS ITEMS HERE`
- `EDIT BLOG ITEMS HERE`

Copy one existing card, paste it below, and change the date, title, and paragraph.

Example news card:

```html
<article class="news-card">
  <span class="news-date">2026</span>
  <h3>Your new update title</h3>
  <p>Your update description goes here.</p>
</article>
```

Example blog card:

```html
<article class="blog-card">
  <span class="blog-tag">Topic</span>
  <h3>Your blog title</h3>
  <p>Short description of the blog post.</p>
</article>
```
