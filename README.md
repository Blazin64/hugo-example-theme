This theme is based on the templates found at [https://gohugo.io/templates/]. A few minor tweaks were made to correct bugs and to make the theme a more realistic example.

### Tweaks:
* Added pagination template  to `layouts/index.html`. ((source here)[https://gohugo.io/templates/pagination/#build-the-navigation])
* Added friendly page listing to `layouts/index.html`. ((source here)[https://gohugo.io/content-management/summaries/#example-first-10-articles-with-summaries])

### Bugs fixed:
* `layouts/index.html` does not render summaries. (outdated syntax)
* `layouts/_default/single.html` generates invalid tag/topic URLs. (missing slashes)
