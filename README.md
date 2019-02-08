# WGUBeamer
Latex Beamer template incorporating the branding of Wrexham Glyndŵr University.

## About this theme

This Beamer template provides a theme for presentations in the corporate style of Wrexham Glyndŵr University. It has been developed unofficially by [https://github.com/jessicadigital/](Jessica Muirhead) based on the popular [https://github.com/matze/mtheme](Metropolis theme) as a basis for branded materials.

If you use this template, please consider contributing to its development.

## Fonts

Due to licensing restrictions, the font files for _Century Gothic Regular_ and _Century Gothic Bold_ have not been included. You will need to source your own copies of these fonts, and include them as `WGUBeamer/century-gothic.ttf` and `WGUBeamer/century-gothic-bold.ttf`.

## LaTeX

The theme has been developed using XeLaTeX on [https://www.overleaf.com/](Overleaf). If you use it within other environments, please raise an issue/pull request and add it to the compatibility table below:

Compiler | Environment  | Compatible?
---------|--------------|--------------
XeLaTeX  | https://www.overleaf.com/](Overleaf) | Yes

## Presentation setup

The template has been designed primarily for 16:9 (widescreen) mode, although it does work for traditional 4:3 formats.

## How to use

Download the full `.zip` package using the `Clone or download` button in the top right. You can then upload the entire `.zip` as a new project in Overleaf.

Edit the `demo.tex` file to create your presentation. By default this uses 16:9 aspect ratio, you can change to 4:3 by deleting the `aspectratio=169` from the top of the source file.

To prepare a `.pdf` for dissemination, add the option `handout` to the `documentclass`. Without this option, you will produce a stepped file including animation frames on every slide that is suitable for presentation.
