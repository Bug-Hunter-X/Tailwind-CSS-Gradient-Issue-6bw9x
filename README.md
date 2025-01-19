# Tailwind CSS Gradient Issue

This repository demonstrates a bug where a Tailwind CSS gradient background does not render correctly across different browsers.  The gradient is defined using `bg-gradient-to-r` along with `from-blue-500` and `to-purple-500` but only displays consistently in certain environments. 

## Steps to reproduce
1. Clone this repository.
2. Open `index.html` in different browsers.
3. Observe inconsistencies in the gradient display.

## Solution
The solution involves ensuring the use of vendor prefixes for the gradient which ensures compatibility across different browsers. 