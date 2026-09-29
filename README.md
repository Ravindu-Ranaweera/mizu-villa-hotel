# MIZU Villa

A one-page site for MIZU Villa, Sri Lanka — a restored colonial bungalow let as a whole house.

Static: one `index.html` and twelve photographs in `img/`. No build step, no dependencies.
The only external request is the Google Fonts stylesheet (Fraunces + Karla).

## Local preview

```
python -m http.server 8000
```

Then open http://localhost:8000

## Deploy

Published with GitHub Pages from the `main` branch, root folder.

## Editing

Contact details live in the `<dl class="contact">` block near the bottom of `index.html`.
The gallery is driven by the `PHOTOS` array in the inline script — add a file to `img/`
and a matching entry there.
