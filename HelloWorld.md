---
title: "HelloWorld.md"
author: "Me"
date: "9/14/2020"
output: word_document
---

```{r setup, include=FALSE}
knitr::opts_chunk$set(echo = TRUE)
```

## This is a markdown file

```{r cars}
summary(cars)
```


```{r pressure, echo=FALSE}
plot(pressure)
```

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot.
