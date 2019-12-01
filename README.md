# ravi-chandran.github.io
This GitHub Pages repository is set up to redirect to my actual blog at: [`https://ravi-chandran.github.io/blog/`](https://ravi-chandran.github.io/blog/
)

The redirect uses the files `_config.yml` and `index.html` in this repository. The approach is based on this wonderful article: [Setup a redirect on Github Pages](https://dev.to/steveblue/setup-a-redirect-on-github-pages-1ok7).

In a nutshell, the redirect is achieved by:
- `index.html`: The `meta` tag with `http-equiv="refresh" content="0"` causes the redirect to the specified URL. In addition, the `link` tag with `rel="canonical"` tells search engines that the two sites have duplicate content.
- `_config.yml`: A theme has to be set here so that GitHub Pages will actually build the repository's master branch as a GitHub Pages site.
