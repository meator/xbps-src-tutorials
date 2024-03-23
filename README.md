# Redirect webpage
This page redirects the reader to https://xbps-src-tutorials.github.io

## 404 status
This page doesn't have any "real" content, the body of this page is kept in
`404.html`. This is done to redirect all links which previously worked to the
`404.html` page.

An advantage of this approach is that the user will receive 404 status when
trying to access this page. To my knowledge, GitHub Pages doesn't provide a way
to send custom HTTP responses. Because of this, A GitHub Page can send two
status codes: 200 and 404. Making it send 404 is more accurate, because this
page is only a stub redirect page.

Using 404 status makes sure that search engines won't index this site. This is
already handled by [noindex](#google), so this is redundant.

## 404.html
`404.html` is kept very minimalistic. Its colorscheme is derived from the Ayu
theme (which is used by default in the book). Because the theme is dark, Dark
Reader is turned off with

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
