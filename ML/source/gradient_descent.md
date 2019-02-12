---
title: Gradient Descent
author: Adam Montgomery
date: 1/29/19
geometry: margin=3cm
output: pdf_document
---

# Overview
Gradient descent is a tool used to minimize
error between some function and actual data.
We use gradient descent to dynamically modify
our function until we reach a line of best fit.
After several iterations, the function will approximate
future data points, allowing us to make predictions.

> The error function
$\sum_{0}^{n}{\sqrt{\left(d(x_i)-f(x_i)\right)^2}}$
gives us the sum of squares of error for each point in the
data set vs our predictive function f(x).

# Usage
