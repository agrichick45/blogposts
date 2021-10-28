2021-10-28-State-Crops
================
Mandy Liesch
10/28/2021

``` r
#code to create the rendering
rmarkdown::render("_Rmd/2021-10-28-State-Crops.Rmd", 
                  output_format = "github_document", 
                  output_dir = "_posts/", 
                  output_options = list(toc=TRUE, toc_depth = 2, html_preview=FALSE))
```

## State Cropping Heatmaps

Have you ever wanted to get a fingerprint on just when and how cropping
dynamics in the United States are changing?

Which areas are heavy producers of corn? How weird are the agricultural
crops grown in North Dakota?

Find out these answers with color intensity heat maps of CONUS [State
Cropping](https://agrichick45.github.io/StateCropping/) from 1990-2021.

[What is a heatmap](https://www.youtube.com/watch?v=Q3XFj3zJBuE)?
