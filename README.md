# sayantan-kuila.github.io

Personal academic homepage of Sayantan Kuila, served by GitHub Pages at
**https://sayantan-kuila.github.io**.

## Structure

```
index.html        the whole site (content + styles in one file)
assets/photo.jpg  profile photo
.nojekyll         tells GitHub Pages to serve files as-is (no Jekyll build)
```

## Editing

Everything lives in `index.html`. The sections are marked with `<section id="...">`:

| Section        | What to edit                                              |
| -------------- | --------------------------------------------------------- |
| `hero`         | Name, role line, affiliation, social links (top of page)  |
| `about`        | Intro paragraphs and the research-interest chips          |
| `publications` | One `<article class="pub">` block per paper               |
| `experience`   | One `<li>` per role in the timeline                       |
| `education`    | One `<li>` per degree                                     |
| `contact`      | Email and links                                           |

To add a paper, copy an existing `<article class="pub">…</article>` block and
change the year, title, authors, and venue. To add a PDF/arXiv link, put an
`<a href="...">PDF</a>` inside the `venue` paragraph.

Commit and push to `main`; GitHub Pages rebuilds automatically within a minute
or so.
