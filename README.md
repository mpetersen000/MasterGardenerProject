# Data Analysis for Santa Clara Master Gardener Club

## Overview

This project went through the full data analysis process to analyze Nextdoor Neighborhood coverage including scraping, gathering, assessing, cleaning, analyzing, visualizing, and reporting.  Data was gathered via files from the Santa Clara County Master Gardener coordinator and by scraping the Nextdoor Web App.

## Background
Since 1981, the University of California Master Gardener Program has been extending UC research-based information about home horticulture and pest management to the public. The UC Master Gardener Program is a public service and outreach program under the University of California Division of Agriculture and Natural Resources, administered locally by participating UC Cooperative Extension county offices. 

The UC Master Gardener Program is an example of an effective partnership between the University of California and passionate volunteers. In exchange for training from the University, UC Master Gardeners offer volunteer services and outreach to the general public in more than 50 California counties. Last year 6,116 active UC Master Gardener volunteers donated 398,265 hours, and 5.4+ million hours have been donated since the program's inception. 

Volunteers complete a 16-week, 60+ hour training program in home horticulture and remain certified on a yearly basis. 

The Master Gardeners of Santa Clara have begun using the Nextdoor App to increase local community outreach. Each week the assigned Master Gardener for a neighborhood will send tips of the week and answer questions.  The Nextdoor App is opt-in.  Each household must sign up with the app and verify thier identity.  The number of residences that are members of Nextdoor is hidden except to a logged in member or to the neighborhood leaders. The Nextdoor platform allows members to communicate with their neighborhood and nearby neighborhoods only. This goal is to provide a sense of connectedness among members.

## Questions to be Answered

* What are all the Nextdoor neighborhoods in Santa Clara County?<br>
* Which Neighborhoods are reached by each Master Gardener?<br>
* Which Neighborhoods do not have a Master Gardener assigned or are not able to be reached?<br>
* What is the interest level in gardening for each Nextdoor Neighborhood?<br>

Analysis and Visualizations can be found in the Jupyter notebook as well as the Tableau Story.

### Languages
Python, Markdown

### Libraries
pandas<br>
numpy<br>
requests<br>
matplotlib<br>
seaborn<br>
json<br>
geojson<br>
BeautifulSoup<br>
shapefile<br>
difflib<br>
pprint<br>
six.moves.urllib<br>
re<br>

### Software
[Jupyter Notebook - MasterGardenerDataWrangling.ipynb](https://github.com/mpetersen000/MasterGardenerProject/blob/master/MasterGardenerDataWrangling.ipynb)

### Analysis Report
[View Tableau Story](https://public.tableau.com/profile/mpetersen000#!/vizhome/SantaClaraCountyMasterGardeners/SantaClaraMasterGardener?publish=yes)
