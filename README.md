# Surface Engineering Lab — Website

Redesigned website for the Surface Engineering Laboratory (Thin Film Lab),
Department of Mechatronics Engineering, Gyeongsang National University.

## Pages

| File | Nav label |
|------|-----------|
| `index.html` | About |
| `members.html` | Members |
| `projects.html` | Projects |
| `publications.html` | Publications |
| `openings.html` | Openings |
| `news.html` | News |
| `style.css` | Shared stylesheet (deep-blue academic theme) |

All pages share `style.css`, so change colors, fonts, or spacing in one place.
The accent colors live in the `:root` variables at the top of `style.css`.

## Publishing on GitHub Pages

1. Create a repository (e.g. `thinfilmlab`) and upload every file in this folder
   to the repository root.
2. In the repository, go to **Settings → Pages**.
3. Under **Build and deployment → Source**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then **Save**.
5. After a minute your site will be live at
   `https://<your-username>.github.io/<repository-name>/`.

To use a custom domain, add a `CNAME` file with your domain and configure DNS.

## Editing tips

- **Add lab members:** in `members.html`, duplicate a
  `<div class="card member">…</div>` block and edit the initials, name, role,
  and research topic.
- **Add a publication:** copy a `<li class="pub-item">…</li>` block into the
  right year group in `publications.html`. Wrap the PI's name in
  `<span class="me">D.-H. Cho</span>` to highlight it.
- **Add news:** copy a `<div class="news-item">…</div>` block in `news.html`.
  You can wrap the `<h3>` in an `<a href="…">` to link to the article.
- **Change the theme color:** edit `--blue`, `--navy`, and `--accent` in
  `style.css`.

## Content source

Content was carried over from the existing site at
`https://sites.google.com/view/thinfilmlab` (About, Members, Projects,
Publications, Openings, News).
