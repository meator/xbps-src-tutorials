# Redirect webpage
This page redirects the reader to https://xbps-src-tutorials.github.io

## Symlinks
This branch contains a lot of symlinks. This is done to make sure that all links
that were previously valid will stay valid. Redirecting to GitHub Pages 404 page
is not acceptable in that case[^1].

## index
Index is kept very minimalistic. Its colorscheme is derived from the Ayu theme
(which is used by default in the book). Because the theme is dark, Dark Reader
is turned off with

```html
    <meta name="darkreader-lock">
```

## Google
This website contains a Google validation token. I, meator, manage it. It is
kept to make sure that the redirect website won't get indexed.

## Redirection
The redirection mechanism is heavily inspired from
https://superdevresources.com/redirects-jekyll-github-pages/ (but without Jekyll
involved).

[^1]: A previous configuration of this website did that, but it provided a
      custom `404.html` which was equivalent to `index.html`. This meant that
      the user was informed that the website was moved, but they still got 404
      which could be seen as more appropriate than 200. See
      269efe09ae7185872a5a9cda95cfa929b37700d4 This was reverted, a true
      redirect is used now.
