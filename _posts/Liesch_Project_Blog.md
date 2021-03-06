Project 1: Pokemon API
================
Mandy Liesch
10/7/2021

-   [Result Synopsis](#result-synopsis)
-   [Reflection](#reflection)
-   [Websites](#websites)

``` r
#code to create the rendering
rmarkdown::render("_Rmd/Liesch_Project_Blog.Rmd", 
                  output_format = "github_document", 
                  output_dir = "_posts/", 
                  output_options = list(toc=TRUE, toc_depth = 2, html_preview=FALSE))
```

# Result Synopsis

I have never actually thought about the factors that impact pokemon
baseline happiness before. I know that pokemon come in all different
shapes, sizes, functions, and densities, but I did not expect happiness
to decrease for heavier pokemon, and decrease over time. Generation 7
includes the Alola Region, which is a region that is very similar to
Hawaii. In this island like paradise, it is difficult to believe that
the pokemon are the heaviest, on average, and not very happy. Maybe the
life of island hopping is much more depressing than it appears? And the
least happy region, on average is the last generation. I believe that
these areas are suffering from mental and physical health consequences
from the invasion of 10 year olds with Indiana Jones complexes, that
want to fight them?

# Reflection

This process was some of the most… maddening and rewarding things that I
have ever done. The data manipuation part and visualizations are things
that I have had a lot of experience with. Interacting with APIs is also
something that I have done before. However, the Pokemon API was the
weirdest interface I have ever dealt with, returning URLs and lists,
rather than datasets and frames. It took so much time and effort to
learn how to create these projects and values.

Functions and wrappers have always felt like this… mysterious and opaque
mountain. I have struggled with them in all programming languages that I
have tried. I had to download and run ALL of the information in the
provided example, and then, I still didn’t have any idea what to do for
MY functions, as the pokemon API required us to create and manipulate
data so differently. It took several hours of watching and reading about
list manipulations and functions, and playing with the example queries
in the pokemon API before I started to even understand HOW to interact
with the data points to get data. Then, I chose one pokemon type, and
one pokemon generation, and manipulated the data until I got the
dataframe to show what it needed. THEN I had to develop the functions.

They were not that bad in the end, I don’t think… but it involved a lot
of good, Wisconsin beer, some nutella, and lots of hopeless frustration
that needed to be pushed through.

And despite my difficulties with functions… I wound up writing 11 of
them, querying 4 different endpoints.

So, triumph indeed!

And you bet I am proud!

# Websites

Link to the [gitHub repository
Vignette](https://github.com/agrichick45/ST558Project1/) Link to the
[gitHub
Readme](https://github.com/agrichick45/ST558Project1/blob/main/README.md)
