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


## Potential Future work
- This can be redone in Tableau, which would allow anyone to add in new data and/or control this visualization in concent with another type of visualization. An example would be someone could select a map area and then only show the points from within that map area on this plot. 
- Make additional fields based on ratios of major elements
- Add a field based on Curisoity's eleveation on Sol of sampling. This would be slightly more geologically useful than Sol. Additionally, you could take additional data about direction and distance of laser strike and the rover's Z position to accurately find the sample elevation if you had a fairly accurate topographic map with sub-centimeter resolution. Ideally, you'd use a geologic cross-section depth number calculated by one of the Mars science team geologist's for each named Martian rock sampled. To my knowledge this last bit of information is not public yet?
- You could use a database of Earth rocks and their rock type categorization to generate a first-pass rock type prediction of Martian rocks based on this dataset. You could even automate the prediction and have it be an optional overlay. 
- Instead of showing every sample, only show an average for each rock as an option?
- Display standard deviation and error on this visualization either by default or an option.

## How to install (will build this out later)
- clone this repo by typing in terminal - git clone https://github.com/JustinGOSSES/datajam_Mars_MajorElements
- cd into the locally cloned repo
- If not already installed on your machine, install python 3, pandas, jupyter, plotly
- in terminal, type  jupyter notebook
- follow the directions that appear in your terminal to open a browser with the running jupyter notebook url if it doesn't open automatically
- press "play" to move through the notebook and run all the cells
- Once you get the visualization to display, use the pink "brush" to change what samples are highlighted. 
  - Clicking on the ends of each pink "brush" will expand its height. Clicking and holding on the center of it as your move the mouse will move it up and down. Each set in the parallel set can have a pink "brush". If there are multiple "brushes" only the samples that occur in all "brushes" will be highlighted. 
