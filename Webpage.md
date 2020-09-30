---
title: "PeerGradedAssignment2"
output: html_document
---

Date: 9/30/2020



# Developing Data Products Project 2


```{r }
library(plotly)
```

## Plot

```{r}
p <- plot_ly(economics, x = ~date, y = ~unemploy / pop)
p
```
