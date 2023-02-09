# DS-Portfolio

**Data Science Portfolio**

Repository dedicated to build my portfolio as data analyst and future data scientist.

## About this repository

In this repository you will find all my data visualization projects, my DataVis assigments, and other extra work for improving by visual communication skill. Specifically for this last part, you could find `R` code for reproducing pre-exising visualizations using both the `graphics` and `ggplot2` `R` packages. In particular, I will reproduce some of the plots created by Cole Nussbaumer, author of the book *Storytelling with data*.


## Reproducing Cole's Plots

In this series, I will reproduce Cole's plots shown in her book *Storytelling with data: a data visualization guide for business professionals* (available [here](https://www.amazon.com.mx/Storytelling-Data-Visualization-Business-Professionals/dp/1119002257)) with the functions available in the `graphics` R package.

### Demo: Tickets Plot

![Cole's Version](/Image/ticket-cole-version.jpg "Cole's Ticket Plot Version")
```{r}
received = c(160,184,241,149,180,160,132,202,160,139,149,177)
processed = c(160,184,231,148,181,150,123,156,126,104,124,140)

# Setting frame
par(bty = "L", col = "lightgray",  col.axis = "lightgray",
    yaxs = "i", xaxs = "i", mar = c(3,3,2,7), xpd = TRUE)

# received line plot
plot(received, type = "l", ylim = c(0,300), xaxt = "n", lwd = 4, col = "gray", yaxt = "n")
points(8:12, received[8:12], pch = 19, col = "gray", cex = 1.5)
text(8:12, received[8:12] + 20, received[8:12], col = "gray")
lines(processed, lwd = 4, col = "darkblue")

# processed line plot
points(8:12, processed[8:12], pch = 19, col = "darkblue", cex = 1.5)
text(8:12, processed[8:12] - 20, processed[8:12], col = "darkblue")
text(12, c(140,177), c("Processed","Received"), col = c("darkblue","lightgray"), pos = 4)

# Axes
axis(1, at = 1:12, labels = month.abb, tick = F)
axis(2, at = seq(0,300,50), col.ticks = "lightgray", las = 1, col = "lightgray")
```
![My Version](/Image/ticket-my-version.jpeg "My R Version")
