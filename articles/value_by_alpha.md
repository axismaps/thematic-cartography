---
layout: page
title: Value-By-Alpha Maps
---

### When to Use

Value-by-Alpha maps are a novel way to incorporate a second data set into a traditional single-theme [choropleth map](../articles/choropleth.html) by using the second variable as an opacity mask (aka "alpha channel") that determines how much of the first data set shows through. In this sense, the second data set "conditions" the choropleth map to show what relationship (if any) might exist between these two themes. Value-by-alpha maps require numerical data and won't work well with categorical data. They inherit many of the same strengths and weaknesses as single-theme choropleth maps which are outlined [here](../articles/choropleth.html). Like all bivariate maps, these maps encode two numbers/facts per location and are, therefore, graphically efficient.

[Value-by-alpha maps were conceived](http://www.axismaps.com/blog/2008/11/a-new-kind-of-election-map/) as an alternative to [bivariate area cartograms](../articles/bivariate_cartograms.html).

### Concerns
All other things being equal, value-by-alpha maps are more difficult to read than univariate choropleth maps because the colors change in a fairly sophisticated way: the saturation encodes one thing while the lightness another. As a result, it is not possible to assume—as you can with simpler choropleth maps—that dark colors mean "more" of something exists. Rather, the colors you see are a result of how the alpha mask interacts with the underlying colors. Be aware that the more general your audience—and the less time folks spending reading it—the more you may want to default to a simpler univariate map.

### Example Map
This map shows the results of the 2008 Presidential Election in the United States. Like many election maps, blue represents votes for Obama and red votes for McCain. The more saturated either color, the greater their margin of victory was for that location. So far, this is just a normal choropleth election map, but the second variable on this map is total population. The greater the number of people in a location, the less the mask obscures the underlying election data. Areas that are very sparsely populated, like rural Montana, are largely blocked by the alpha mask (despite being geographically quite large). On the other hand, Chicago may be geographical small, but its large population means that the alpha mask lets it show through so that it stands out more on the map and looks, relatively speaking, more important. And in an election it is, in fact, more important: More votes are at stake in highly populated centers, which stand out on the map.

![](../images/alpha_map.jpeg)

For a more detailed discussion of value-by-alpha maps, look at this [summary by Andy Woodruff](http://andywoodruff.com/blog/value-by-alpha-maps/).