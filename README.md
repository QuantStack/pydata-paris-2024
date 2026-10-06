# PyData Paris 2024 — archived site

A static archive of the PyData Paris 2024 conference site, rebuilt from the
original content. Published with GitHub Pages.

## Layout

```
index.html, about.html, ...   one file per page, at the repository root
site.css                      the entire stylesheet (hand-written, ~250 lines)
images/                       photography, logos and other page images
```

There is no build step, no framework and no JavaScript bundle. The only external
resources a page loads are the Montserrat webfont (Google Fonts, SIL Open Font
License) and, on the schedule page, the Pretalx schedule widget served from
pretalx.com.

## GitHub Pages

Serve from the `main` branch, `/` (root). All links are relative, so the site
works from a project subpath such as `https://<org>.github.io/pydata-paris-2024/`.

## Notes

- Ticket sales and the shopping cart have been removed; they were handled by an
  external service that is no longer active.
- The schedule page embeds the live Pretalx widget, so it needs network access
  to render and reflects whatever that event's schedule currently contains.
- PyData is a registered trademark of NumFOCUS, Inc. Site content is
  © QuantStack S.A.S.
