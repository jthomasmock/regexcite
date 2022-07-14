
# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to demo sending `pkgdown` to RStudio Connect via Git-backed deployment.

You can generate the necessary manifest file via:

```r
rsconnect::writeManifest("docs", list.files("docs"), "index.html", contentCategory = "site")
```

Published example on RSC: [https://colorado.rstudio.com/rsc/content/e1e7aa54-385a-49b9-b9e9-005465ec21c3/](https://colorado.rstudio.com/rsc/content/e1e7aa54-385a-49b9-b9e9-005465ec21c3/)
