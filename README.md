# DS-Portfolio
Repository dedicated to build my portfolio as data analyst and future data scientist.

## What you will find here


## Reproducing Cole's Plots

In this series, I will try to reproduce Cole's plots shown in her book *Storytelling with data: a data visualization guide for business professionals* (available [here](https://www.amazon.com.mx/Storytelling-Data-Visualization-Business-Professionals/dp/1119002257)) with the functions available in the `graphics` R package.

### Demo: Tickets Plot

![Cole's Version](/Image/ticket-cole-version.jpg "Cole's Ticket Plot Version")
```
received = c(160,184,241,149,180,160,132,202,160,139,149,177)
processed = c(160,184,231,148,181,150,123,156,126,104,124,140)

par(bty = "L", col = "lightgray",  col.axis = "lightgray",
    yaxs="i", xaxs="i", mar = c(3,3,2,7), xpd = TRUE)
plot(received, type = "l", ylim = c(0,300), xaxt = "n", lwd = 4, 
     col = "gray", yaxt = "n")
points(8:12, received[8:12], pch = 19, col = "gray", cex = 1.5)
text(8:12, received[8:12] + 20, received[8:12], col = "gray")
lines(processed, lwd = 4, col = "darkblue")
axis(1, at = 1:12, labels = month.abb, tick = F)
axis(2, at = seq(0,300,50), col.ticks = "lightgray", las = 1,
     col = "lightgray")
points(8:12, processed[8:12], pch = 19, col = "darkblue", cex = 1.5)
text(8:12, processed[8:12] - 20, processed[8:12], col = "darkblue")
text(12, c(140,177), c("Processed","Received"), col = c("darkblue","lightgray"),
     pos = 4)
```
![My Version](/Image/ticket-my-version.jpeg "My R Version")
