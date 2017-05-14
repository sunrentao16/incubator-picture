---
title: "Recipe project Incubator"
author: "Rentao Sun"
date: "May 13, 2017"
output: html_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

# get recipe data from web & clean data ###
```{r, warning= F, message=FALSE}
library(rvest)
library(lubridate) # time duration
# get links function
source("get_links.R")
# modify url_table
source("modify_url_table.R")
# get recipe from one url
source("get_recipe.R")
# get recipe form a table of urls, return a list of recipe
source("get_all_recipes.R")
# convert recipe_list to a data frame
source("convert_to_df.R")
```
