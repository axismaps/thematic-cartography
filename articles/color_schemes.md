---
layout: page
title: Using Colors on Thematic Maps
---

### Controlling the Three Dimensions of Color

The success of many thematic maps, such as [choropleth maps](../articles/choropleth.html), depends upon understanding how we manipulate colors to systematically encode our geographic data using the three dimensions of color: **hue, lightness,** and **saturation**. Unlike picking colors for your living room, the use of color on maps is far less subjective than most people suspect and we don't pick the colors on maps simply because "they look nice." Rather, there are important rules that govern how color schemes work and how those colors relate to the data. Furthermore, there are important perceptual constraints that are well known, such as red-green colorblindness (affecting roughly 8% of males), which require we design with these issues in mind and not merely pick what looks nice to us personally. The good news is that the rules that govern how to use color on maps, as well as solutions to problems like red-green color blindness, are well understood and fairly easy to follow.

### The nature of your thematic data dictates what kind of color scheme you need

Nominal data are categories that are inherently unorderable (like soils or landuse) and should only be mapped with **nominal color schemes**. If you have orderable categories (such as low/med/high) or if you have numerical data, a **sequential color scheme** is what you need. Sequential color schemes can be single or multi-hue, but they are dominated and ordered by differences in lightness/saturation. **Diverging schemes** should only be used when your data has a natural mid-point such as a zero (e.g., positive and negative change/growth) or if you want to compare places to something like the national average (e.g., county data showing places that are above and below the national average for a variable like per capita income). A good place to find color schemes of each type is [ColorBrewer](http://www.ColorBrewer2.org), where you can also find more detailed discussions of their characteristics.

![](../images/color_schemes.jpg)

### Perceptually-Graded Schemes

The color schemes in ColorBrewer are perceptually graded ([pdf](http://www.geography.wisc.edu/~harrower/pdf/ColorBrewer2003.pdf)) so that the amount of color change in each color step looks consistent to our eyes. We have to do this because humans do not perceive differences in all hues equally well. Making professional color schemes like this isn't easy, especially if you are varying all three dimensions of color simultaneously as many of the multi-hue sequential and diverging scheme dos. While you shouldn't feel restricted to [ColorBrewer](http://www.ColorBrewer2.org), it does provide tested, reliable color schemes to get you started.