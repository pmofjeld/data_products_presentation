---
title       : Fractal GIF Maker
subtitle    : Data Products Course Project Presentation
author      : Paul Mofjeld
framework   : revealjs        # {io2012, html5slides, shower, dzslides, ...}
revealjs: {theme: moon, transition: cube}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Fractal GIF Maker

### Course Project Presentation

#### Author: Paul Mofjeld

---

## The App

Fractal GIF Maker is a shiny app which allows you to create and view .gif images of fractals in the complex plane (the realm of imaginery numbers).

---

## Features

* View fractals at any region of the complex plane; at any resolution (so long as it's square).
* Allows for flexible customization of the fractal generating function. Experiment!

---

## Default Behavior

By default, the app will produce a gif of the first 20 iterations of the famous Mandelbrot Set. It is meant to closely emulate an example from R's wikipedia page (the inspiration for this project).

---

## Obligatory R Code


```r
2+2
```

```
## [1] 4
```
