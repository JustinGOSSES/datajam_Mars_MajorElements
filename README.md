# datajam_Mars_MajorElements

datajam Mars MajorElements Parallel Sets Python Plotly

## What is this?
The results of a data jam run by Houston Data Visualization meetup. 

## When?
3-4 hours on Saturday morning July 22nd, 2017. Hosted at "Station", Houston, Texas.

## What 
Major element data from all ChemCam rock sample data from start of MarsScienceLaboratory (Curiosity Rover) till today. 

## Purpose
Wanted to interactively view ratios of different oxides and view every sample but also view clusters within the whole. 

## Used
Used pandas and plot.ly using the python language and built in the Jupyter notebook


## Result
![plot image](https://github.com/JustinGOSSES/datajam_Mars_MajorElements/blob/master/ScreenShot_Plot.png)
image https://github.com/JustinGOSSES/datajam_Mars_MajorElements/blob/master/ScreenShot_Plot.png

- The pink bits on the image above are dragable and expandable "brushes". The samples "brushed" are colored but the ones that are not appear gray. This provides a way to see clusters within the whole, which is messy. 

- The color bar is based on "Sol" or martian day after first data collected


![plot image](https://github.com/JustinGOSSES/datajam_Mars_MajorElements/blob/master/ScreenShot_HighCa_OnlyEarlyDay.png)
image https://github.com/JustinGOSSES/datajam_Mars_MajorElements/blob/master/ScreenShot_HighCa_OnlyEarlyDay.png

- This plot shows that almost all the high CaO data comes from relatively early Sols.
- This suggests how this type of interactive plot could be used to ask questions and quickly get answers.
- In the future, it would be better to look at this data with the color based on elevation or geologic section position as opposed to Sol. 


## Future work
This can be redone in Tableau, which would allow anyone to add in new data and/or control this visualization in concent with another type of visualization. An example would be someone could select a map area and then only show the points from within that map area on this plot. 

## How to install (will build this out later)
- clone
- cd into repo
- If not already there, install python 3, pandas, jupyter, plotly
- in terminal, type       jupyter notebook
- place play to move through notebook and run cells
- play around with pink "brush"
