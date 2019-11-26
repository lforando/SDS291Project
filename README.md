# SDS291Project
SDS 291: Multiple Regressions - Group Project

---
title: ""
authors: "Lauren Forando, Elle Jo Whalen, Jemimah Charles"
date: December 10, 2019
output: 
---

```{r}
library(readxl)
library(tidyverse)
library(mosaic)
```

```{r, message = FALSE}
#Bringing in our dataset
bodyfat <- read_excel("~/Desktop/bodyfat.xlsx")
attach(bodyfat)
glimpse(bodyfat)
```
