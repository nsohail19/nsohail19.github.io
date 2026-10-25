# nsohail19.github.io

Personal website for Noor Sohail, served by GitHub Pages at <https://nsohail19.github.io>.

Plain HTML and one stylesheet: no build step, no frameworks, no JavaScript.

## Structure

```
index.html              About (home page)
experience.html         Positions and education
publications.html       Papers and selected presentations
teaching.html           HBC training workshops and mentorship
beyond-the-lab.html     Personal page
css/style.css           All styling; colors and fonts are set at the top in :root
favicon.svg             Browser-tab icon
files/                  Downloadable documents (Noor_Sohail_CV.pdf)
img/                    Images, grouped by page (logos/, publications/, teaching/, beyond/)
```

## Common updates

- **New CV:** replace `files/Noor_Sohail_CV.pdf` with the new PDF, keeping the same file name.
- **New publication:** copy one `<li class="pub">` block in `publications.html` and edit it.
  Wrap your name as `<span class="me">Sohail N</span>` so it shows in bold color.
  Thumbnails go in `img/publications/` (about 400 px wide).
  Without an image, use `<div class="pub-thumb placeholder">Journal</div>`.
  Topic tags go in `<div class="pub-topics">` as `<span class="topic">Cancer</span>`.
  Each paper has an `id` (e.g. `barriga2022`) that the About page's research-interest cards link to,
  so if you add a paper to a topic, also add a link on that card in `index.html`.
- **Header and nav:** they are repeated at the top of every page. If you change them, change all five pages.
- **Colors:** edit the variables under `:root` at the top of `css/style.css`.
