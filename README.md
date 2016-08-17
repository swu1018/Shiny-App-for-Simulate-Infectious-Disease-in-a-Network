# A shiny app to simulate infectious disease in a network 

This is a shiny app for visualizing the spread of SIR-like infectious disease in a network.

## Screenshots


<p align="center">
  <img src="https://github.com/alisonswu/shiny-SimNetwork/screenshot1.png" width="350"/>
  <img src="https://github.com/alisonswu/shiny-SimNetwork/screenshot2.png" width="350"/>
</p>

## Usage

You will need Rstudio and internet connection to run the app.

To launch the app, open Rstudio and run the following code. 

```R
# install shiny package if not done
# install.packages("shiny")

library(shiny)

runGitHub("shiny-SimNetwork","alisonswu")

