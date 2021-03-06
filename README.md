[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

An interactive [tool](https://jhelvy.shinyapps.io/splitkbcompare/) for comparing layouts of different split mechanical keyboards.

## Supported keyboards

In order of number of keys:

- [ErgoDox (76 - 80)](https://github.com/Ergodox-io/ErgoDox)
- [ErgoDash (66 - 72)](https://github.com/omkbd/ErgoDash)
- [Redox (70)](https://github.com/mattdibi/redox-keyboard)
- [Keyboardio (64)](https://github.com/keyboardio)
- [Nyquist (60)](https://github.com/keebio/nyquist-case)
- [Lily58 (58)](https://github.com/kata0510/Lily58)
- [Iris (54 - 56)](https://github.com/keebio/iris-case)
- [Kyria (46 - 50)](https://github.com/splitkb/kyria)
- [Gergo (46 - 50)](https://www.gboards.ca/)
- [Corne (42)](https://github.com/foostan/crkbd)
- [Atreus (42)](https://github.com/technomancy/atreus)
- [Elephant42 (42)](https://github.com/illness072/elephant42)
- [Minidox (36)](https://github.com/dotdash32/Cases/tree/master/Minidox)
- [Gergoplex (36)](https://www.gboards.ca/)
- [Georgi (30)](https://www.gboards.ca/)

## Screenshot:

![](images/screenshot.png)

## Detailed description:

This app is an interactive tool for comparing layouts of different split mechanical keyboards, built for the DIY [ergonomic keyboard community](https://www.reddit.com/r/ErgoMechKeyboards/).

Typing at your computer for multiple hours every day can lead to multiple health issues, such as [Repetitive Strain Injury (RSI)](https://en.wikipedia.org/wiki/Repetitive_strain_injury). Using a split keyboard design offers an ergonomic solution, but finding which keyboard is right for you can be costly and difficult. Most split keyboards come as DIY kits, making it difficult (if not impossible) to compare different keyboard layouts prior to building them. This app offers a solution to this problem.

Using the [magick library](https://cran.r-project.org/web/packages/magick/vignettes/intro.html), this app overlays images of different keyboard layouts of the user's choosing. The app dynamically changes the colors of each keyboard image in real time to help identify the contours of each different keyboard.

Supported features include:

- A filter for whether or not the keyboard has a number row at the top.
- A filter for the degree of stagger across the key columns.
- A filter for the maximum number of keys.
- A "print" button that downloads a PDF of the keyboard layout image that is accurate to true scale when printed on 8.5 x 11 inch paper.

This app was built using the [R shiny package](https://shiny.rstudio.com/). Shiny apps are typically used to display data and create interactive dashboards. In contrast, while there are no analyses or plots in this app, the images shown are extremely useful for the community of ergonomic keyboard users and hobbyists. The app highlights the power of libraries like [magick](https://cran.r-project.org/web/packages/magick/vignettes/intro.html) for image manipulation in R and the flexibility of the R ecosystem by enabling the manipulated image to be inserted into a RMarkdown document and converted into a true-to-scale PDF.
