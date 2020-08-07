---
title: ssssss
date: 2020-08-06T09:08:39.768Z
subtitle: ddddd
summary: asdasdasd
draft: false
---

aaaaa
```{r diamond, fig.cap='diamonds plot with ggplot2.', tidy=FALSE}
library(ggplot2)
ggplot(diamonds, aes(x=carat, y=price, color=clarity)) + geom_point()
```
