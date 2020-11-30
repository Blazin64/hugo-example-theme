This example theme is based on the templates found at https://gohugo.io/templates/. A few minor tweaks were done to make the theme a more realistic example.

Note: Please use the [GitLab repository](https://gitlab.com/Blazin64/hugo-example-theme). The [GitHub repository](https://github.com/Blazin64/hugo-example-theme) is only a mirror.

### Reference:
Click the file names to see the Hugo documentation pages the code came from.
* [`theme.toml`](https://gohugo.io/contribute/themes/#create-a-theme-toml-file)
* [`layouts/404.html`](https://gohugo.io/templates/404/#404-html)
* [`layouts/index.html`](https://gohugo.io/templates/homepage/#example-homepage-template)
* [`layouts/_default/baseof.html`](https://gohugo.io/templates/base/#define-the-base-template)
* [`layouts/_default/list.html`](https://gohugo.io/templates/lists/#add-content-and-front-matter-to-list-pages)
* [`layouts/_default/single.html`](https://gohugo.io/templates/single-page-templates/#posts-single-html)

### Improvements:
* Added [pagination template](https://gohugo.io/templates/pagination/#build-the-navigation)  to `layouts/index.html`.
* Added [friendly page listing](https://gohugo.io/content-management/summaries/#example-first-10-articles-with-summaries) to `layouts/index.html`.
* Cleaned up messy previous/next post links in `layouts/_default/single.html`.
* Added missing [Hugo generator tag](https://gohugo.io/variables/hugo/) to `layouts/_default/baseof.html`.

### Bugs fixed:
* `layouts/index.html` does not render summaries. (outdated syntax)
* `layouts/_default/single.html` generates invalid tag/topic URLs. (missing slashes)
