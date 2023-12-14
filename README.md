# Ternary_light

Bookdown documentation and code for estimating the light extinction coefficient 
for DOC, Algae, and Non-Algal Particles in inland waters (including estuaries) 
of the conterminous US.

To render bookdown, open Ternary_light.Rproj and run the following command in 
the R console:

bookdown::render_book(input = "src", config_file = "_bookdown.yml")

Note that if you are running locally, you will likely have to change your 
working directory so that both running chunks in line and rendering 
are functional. To run code inline, change the working directory using the
following command in your R console:

setwd("src/")

You will need to "undo" that if you go to render the bookdown:

setwd("..")
