# Optimized-portfolio

## Overview

This project was completed for Udacity's Front End Nanodegree Program. The goal of the project was to optimize the websites load time and animation speeds.

## Viewing the page

Download the project in zip format. Once done, just double click on index.html to find the portfolio optimization.
On the view folder you can find pizza.html to see the fps optimization project

## Optimizing portfolio index.html

1. Used a media query to prevent the print.css from render blocking
2. inlined all the style file and removed white space using css optimizer
3. Compressed and reduced dimension
4. Insight speed of more than 90% in both mobile and desktop

## Optimizing online pizza in pizza.html

1. Used document.getElementBy insted of query selector all to get the access of DOM faster
2. Variable which was in loop unnecessarily is defined outside
3. Seperate loop to prevent recalculating layout and style
4. Instead of 200 pizza images, only 35 pizza will be looped because at one frame around 35 pizza will be showed
5. Style inlined to get a insight score of over 90%.

##Reference
Udacity forum
