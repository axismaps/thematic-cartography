---
layout: guide
title: Standardizing Data
slug: Standardizing Data
nav: Guide
categories: data
order: 202
redirect_from: /guide/standardize/
---

### To Standardize or Not?

A very important consideration in thematic mapping is whether you want to present your data as **raw counts / totals** (e.g., the population of each country) or if you want to standardize your data to create **rates / ratios** (e.g., number of people in a each country _divided_ by the area of that country = number of people per square mile/km). In this population example, the raw counts tell you how many people exist in each country, and the ratio tells you how tightly packed-in those people are. One of the primary reasons to **standardize** (or **normalize**) your data is to allow your readers to compare places that are very different. For example, you can directly compare a large place (like Canada) with a smaller place (like Switzerland). Although Canada has more people than Switzerland, it has a far lower population density; without standardization, that fact might not be obvious.

**NOTE:** If you want to make a [choropleth map]({{site.baseurl}}/guide/univariate/choropleth), you MUST map only standardized data.

**Bottom line:** If you want your map readers to understand _magnitudes_ (how much of something exists), use map totals/counts. If you want your map readers to understand _relative differences_ (that account for things like size differences), use standardized data.

### Are My Data Already Standardized?

The might be! If the numerical data you are about to map are listed as "_x per square mile/km/..._" or "_x per capita_" or "_percent_" or "_ratio of x / y_" then you can skip the data standardization step.

### How to Standardize Your Data
The two most common ways to standardize our data are to divide the data by (1) **the area of the enumeration units**—creating "_x per square mile/km_" data—or (2) by **the number of people within those places**—creating "_x per capita_" or "_x as a % of the total population_" data.