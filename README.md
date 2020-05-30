# Interactive Choropleth Map 

Top 10 grossing states of the United States breakdown. It has the population and gross totals according to 
race of African Americans and White Americans.

## Introduction

This application only has the 10 states highlighted with the choropleth colors to coincide with the legend. 
The legend gives a color variation for amount of people that live in a that actually in that state. The higher the population
the deeper the blue color. The smaller population the less blue and more red. The hover tool give a list of the total population, 
total that grosses 200K or more, black population, white population, black total that grosses 200K, and white total that 
grosses 200k. 


## Technologies

You can use Rstudio to view code and any broswer to display the html file. There are some imports that are needed 
in order for program to work properly. This program uses the leaflet import to support the map of the United States.

```library(dplyr)
library(ggplot2)
library(ggmap)
library(htmltools)
library(leaflet)
library(sp)
library(rgdal)
```

## Launch
To run project you will need an IDE that can allowing data visualization coding:
R Markdown (v2) documents, Shiny apps, and RStudio IDE / the R console
