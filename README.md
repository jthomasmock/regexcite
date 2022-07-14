
# regexcite

<!-- badges: start -->
<!-- badges: end -->

The goal of regexcite is to demo sending `pkgdown` to RStudio Connect via Git-backed deployment.

You can generate the necessary manifest file via:

```r
rsconnect::writeManifest("docs", list.files("docs"), "index.html", contentCategory = "site")
```

