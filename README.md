DRUG OVERDOSE DEATHS - DATA VISUALIZATION PROJECT - BY RICHA GUPTA (ID: RICHAG2)

Drug Overdose remains a major concern in United States. According to CDC, 136 people die every day from an opioid overdose. Nearly 841,000 people have died since 1999 from a drug overdose. In 2019, 70,630 drug overdose deaths occurred in the United States. 
Opioids currently are the main driver of drug overdose deaths. 72.9% of opioid-involved overdose deaths involve synthetic opioids. Opioids were involved in 49,860 overdose deaths in 2019 (70.6% of all drug overdose deaths). 

Dataset used in the visualization is publicly available at CDC.gov site. This visualization uses only part of the dataset that consists of the Drug overdose death rates within all the states and regions in the Unites States for 2017, 2018 and 2019 years. Some data cleaning and manipulation is performed to add relevant data wherever it was missing.


From 2018 to 2019, the largest increase in death rates involving synthetic opioids occurred in the West. Previously, the East had the highest increases in deaths involving synthetic opioids. No state experienced a significant decrease from 2018-2019.


The visualization follows an interactive slideshow method where user exploration is allowed at some steps or scenes of the story. First 2 webpages introduces the user to the subject. Navigation bar to the right also prompts the user to keep scrolling and further explore. Placement of charts keeps the interest of the user with fluorescent colored buttons inviting the user to further drill down in each chart. 
Because drug overdose is such an increasing problem in the country, it makes perfect sense to explore the different states and regions of the country, where this is an increasing epidemic.


Narrative visualization is made up of 4 fundamental elements:


Scenes: These are the charts or slides in the visualization. I have used HTML, CSS, Javascript and D3.js to develop the static webpages. The first webpage showcases the title and the second provides an overview of the Drug Overdose pandemic within the United States. As one scrolls to transition from one webpage to the other, the third webpage is the chart of Unites States map that showcases statewise total overdose deaths. The color legend shows how color scheme changes according to Total number of deaths in the state, with higher deaths having darker color. Two other charts used are bubble and bar chart. Bubble chart provides the ability to show the groupings either by state or region. Bar chart shows the drug wise distribution of each year.


Annotations of charts: There are total 3 charts in this visualization – Map, Bubble and Bar chart. Every chart has a title, label and buttons that can be used as filters to filter the chart to display overdose deaths of the filtered year using state-wise, region-wise and drug-wise distribution. The placement of the chart is in center of the page and size encompasses the entire page. Tooltips are added to give detailed information to drill down on each state showing the number of total deaths for the state. US map also shows in the tooltip, a breakdown of total deaths by each drug type as a list. ‘Total Deaths’ color legend helps the user to distinguish from regions with high overdose deaths to some of the low ones.


Bar chart shows which drug causes the most drug overdose deaths, and by far Synthetic opioids topped the charts for the years 2018 and 2019. The chart has axes and also hovering displays a tooltip that shows the top three and the bottom three states in total deaths related to that opioid. Just like the size of the bar showcases the number of deaths in bar chart, size of the bubbles and color in bubble chart showcases the overdose deaths, darker being higher concentration. There are 2 other buttons which when clicked groups the deaths either region-wise or state-wise.


Parameters are variables that are used in a chart. Main parameters of this story are total number of drug overdose deaths by year, state, region and death occurred by which type of drug, like prescription opioid, heroin, synthetic opioid or other drugs. For example, California, Texas, Florida and Northeast states seem to have much more drug overdose deaths than other states. Every chart has buttons to select the year to show the mortality number for the selected year. When a particular year is selected, the scene changes to show the data for that year. Bubble chart also has a state-wise grouping and region-wise grouping button to group using states or regions, which further triggers to create the groups showcasing the different states. 


Triggers are connections between parameters and are used to transition between charts and interact with the visualizations. Every chart has several buttons that are brightly displayed inviting the user to further explore to change the display. When a year is selected, the map changes state to show the deaths data based on the selected year including the legend. Bubble chart also has a provision, on click of a button, it either shows state-wise deaths or region-wise deaths. Supplementing this, there are various tooltips displayed to give further information to the user.


USEFUL LINKS:

GITHUB link: https://github.com/Richag2/DrugOverdoseDeathsInUS

URL to the visualization: https://richag2.github.io/DrugOverdoseDeathsInUS/

Dataset link: https://www.cdc.gov/drugoverdose/deaths/index.html

CITATIONS/REFERENCES:

https://bl.ocks.org/john-guerra/0d81ccfd24578d5d563c55e785b3b40a

https://vallandingham.me/bubble_charts_in_d3.html

https://github.com/bikramkawan/D3

https://www.cdc.gov/opioids/basics/epidemic.html
