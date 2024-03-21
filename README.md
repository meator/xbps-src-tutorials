# Redirect webpage
This page redirects the reader to https://xbps-src-tutorials.github.io

## Symlinks
This branch contains a lot of symlinks. This is done to make sure that all links
that were previously valid will stay valid. Redirecting to GitHub Pages 404 page
is not acceptable in that case.

## index
Index is kept very minimalistic. Its colorscheme is derived from the Ayu theme
(which is used by default in the book). Because the theme is dark, Dark Reader
is turned off with

```html
    <meta name="darkreader-lock">
```

## Google
This website contains a Google validation token. I, meator, manage it. It is
kept to make sure that the redirect website won't get indexed. The

```html
    <meta name="robots" content="noindex">
```

is present to prevent indexing.
