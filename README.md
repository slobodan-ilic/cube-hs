# cube-hs
Haskell library for 2nd order data analysis of Crunch.io cube responses

# intro
Crunch.io is a platform for statistical data analysis. As part of its functionality it can create so called cubes. These represent 2D (but sometimes also 1D or 3D) aggregate analyses of response data. The main goal is to determine statistical significance of certain category intersections. For example, giving an answer to "What is the percentage of people younger than 25, which are male, and also democrat". Crunch.io server only calculates the basic aggregate data (just counts). To be able to come up with the percentages, we have to _extract_ this data ourselves (on client side). This library is an attempt to make a universally distributable package for enabling such a task.

# wip
