---
date: "2016-11-05T20:22:08+05:30"
draft: false
image: img/portfolio/nba.png
showonlyimage: true
title: NBA Shotmaps Application
weight: 3
---


This small web application was built to display positional shot data from NBA games from the 2021-2022 season. It cleanly combines the declarative nature of Svelte with the utility of D3 scales to plot a base court and overlay positional data with hover animations and tooltips. It features a zoomable, scaleable SVG viewer wrapper component, so a user can zoom in on the court and see every shot taken for any NBA game.
<!--more-->

![](/viz/img/portfolio/nba.png)

The application's underlying data was queried and cleaned from the NBA website in R, cleaned, and processed into JSON to be used in the application itself.

The full reporting can be found here:

https://nba-shotmaps.vercel.app/
