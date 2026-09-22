# Unfiltered Shreyash — Travel Portfolio

Personal portfolio website for **Shreyash Waghmare** — full-time travel vlogger and blogger covering Bharat, one state at a time.

- 🎥 YouTube: [Unfiltered Shreyash](https://www.youtube.com/@yashwaghmare0902)
- ✍️ Blog: [Shreyash Vlogs on Blogger](https://unfilteredshreyash.blogspot.com/)
- 📞 Contact / collab: +91 72496 10733 (call or WhatsApp)

## About this site

A single-page, self-contained portfolio built with plain HTML, CSS, and vanilla JavaScript — no build step, no dependencies. It includes:

- Responsive layout (mobile, tablet, desktop)
- Light/dark mode toggle (saved per visitor)
- The 12 Indian states explored so far, with room to add more
- Latest vlogs and blog posts, linking out to YouTube and Blogger
- A floating WhatsApp button for quick contact
- A collaboration form for tourism boards / brands that generates a pre-filled WhatsApp message — no backend required

## Running locally

This is a single file — just open `index.html` in any browser. No install, no server needed.

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
open index.html   # or double-click the file
```

## Deploying with GitHub Pages

1. Push this repository to GitHub.
2. Go to **Settings → Pages** in the repo.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`.
4. Choose the `main` branch and `/ (root)` folder, then **Save**.
5. Your site will be live at `https://<your-username>.github.io/<repo-name>/` within a couple of minutes.

## Updating content

All content lives in `index.html`:

- **States visited** — the `#states` section's `.state-card` elements
- **Vlogs** — the `#videosGrid` cards (each links to a YouTube video)
- **Blog posts** — the `#blogsGrid` cards (each links to a Blogger post)
- **Contact info / WhatsApp number** — search for `WA_NUMBER` in the `<script>` at the bottom

## License

Personal project — all content and branding belong to Shreyash Waghmare.
