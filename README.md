# Calculating-Max-Print-Size
How to calculate max print size using calculus, specifically Solids of Revolution

## Method
- Using Solids of Revolution, a calculus 2 method you can then calculate your max print size.

## Why
- This method is useful when you are trying to figure out how large of a print you are able to print on a certain 3D printer. As all 3D printer beds are not the same size.
- I decided this project during an internship when designed a mechanical gear for one of my internal projects I was given during my internship.

## Formula
- Standard Solids of Revolution formula: V = ∫ π [f(x)]² dx
- In this case your limits will be the size of your print bed. Mine being 220x220x250mm^3
- Using parabola to solve for missing values : y=ax^2+bx+c

## Output
- My Vmax was = 1,512,500pi cubic mm
- Following you will then solve for V = pih (R^2 out - R^2 inner) which roughly = 215,750 cubic mm
- This closely resembles my auto max size given by the slicer following tolerance 
