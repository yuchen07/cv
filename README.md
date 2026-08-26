# Personal homepage

Source for my personal homepage — a static, dependency-free academic page
published with GitHub Pages from the `cv` repository.

## Layout

```
index.html        the whole page
assets/style.css  all styling (light + dark, print stylesheet included)
.nojekyll         tells GitHub Pages to serve the files as-is
```

## Editing

Open `index.html` and edit the text directly. Each entry under Experience,
Education and Projects is one `<article class="entry">` block — copy an
existing one to add another.

## Preview locally

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```

## Publishing

Push to `main`. GitHub Pages redeploys automatically within a minute.
