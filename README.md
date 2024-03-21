# You're likely looking at the wrong repo. For xbps-src-tutorials, go to https://xbps-src-tutorials.github.io/ or https://github.com/xbps-src-tutorials/xbps-src-tutorials.github.io
# Website migration
xbps-src-tutorials was migrated to https://xbps-src-tutorials.github.io/. This
was done for three reasons:

1. the url is shorter & more concise
1. it allows for nicer search engine indexing

   To give an example, Google doesn't show the favicon for
   `https://meator.github.io/xbps-src-tutorials/` because it [doesn't like
   subdirectory-level home
   pages](https://developers.google.com/search/docs/appearance/favicon-in-search).
1. it lets me fix up the directory structure

   The URLs of the old webpage were too long and had questionable directory
   structure. For example

   ```
   https://meator.github.io/xbps-src-tutorials/xbps-src-tutorial/packaging-j4-dmenu-desktop.html
   ```

   includes `xbps-src-tutorial` twice.

   Because a breaking change already will be made because of the first two
   reasons, it won't hurt much to also fix this problem.

The website is also still "in its infancy". It is best to make these breaking
changes early and then be stable.

# Website
Website itself is located in the `gh-pages` branch.

# Contributing
This website is a stub. It doesn't accept contributions. Go to
https://github.com/xbps-src-tutorials/xbps-src-tutorials.github.io if you want
to contribute to xbps-src tutorials.
