# Tailwind CSS Centering Issue

This repository demonstrates a common issue encountered when using Tailwind CSS to center text within a div that has padding and rounded corners.  The text fails to align vertically as expected.  The solution is shown in `bugSolution.js`

## Problem

The issue stems from the interaction of padding and the `text-center` class.  The padding around the text element prevents accurate vertical centering.  The solution below addresses this. 

## Solution

The provided solution uses flexbox to easily achieve the vertical and horizontal centering.