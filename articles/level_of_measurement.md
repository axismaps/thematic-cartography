---
layout: page
title: Level of Measurement&#58; Nominal, Ordinal, and Numerical Data
---

### Know Your Data

The success of many thematic maps depends on matching the right data with the right kinds of map symbols. In other words, not all geographic data are the same, nor can they all be mapped in the same way. For example, an [area cartogram](../articles/cartograms.html) works great for things like _population totals_ or _life expectancy_ (which are numbers), but it doesn't work with categorical data, especially if those categories are inherently unorderable, such as _dominant religion_ or _soil types_, since no category there is inherently "more" than one another, they're just different kinds of things. Area cartograms need numbers in order to scale the sizes of places; without numbers, there is nothing drive the map symbols. The same is true with [graduated symbol maps](../articles/proportional_symbols.html), [choropleth maps](../articles/choropleth.html), and [dot density maps](../articles/dot_density.html).

What follows is a brief overview of the concept of "level of measurement". For more detailed discussion about each of the map types themselves—and what kinds of data they support—follow the appropriate links.

### Level of Measurement

> **Numerical Data** are the real engine that fuels thematic maps. Anything that can be counted (e.g., people, barrels of oil) or measured (e.g., temperature, income) makes for great thematic thematic maps. One important issue to consider when using numerical data is whether [you should standardize your data](../articles/standardize.html); this can change what kinds of maps you can (and can't) use.
> 
> **Nominal Data** (also known as categorical or qualitative data) are categories that are inherently unorderable, such as _dominant religion, soil types_, or _land-use categories_. They have no numbers attached to them, nor are they rankable—they're merely _different kinds of things_.
> 
> **Ordinal Data** are inherently _orderable categorical data_ like shirt sizes (s / m / l / xl), flood risk (low risk / medium risk / high risk) or age (young / middle aged / old). Mapping ordinal data is best done with a [classed choropleth map](../articles/choropleth.html) with a [sequential color scheme](../articles/color_schemes.html), or as a [graduated symbol map](../articles/proportional_symbols.html) in which the number of classes is equal to the number of data categories you have.
