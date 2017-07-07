# Coursera: Reproducible Research
## Assignment 2
This repository contains the analysis for the Storm data as part of Assignment 2 of the Coursera course on Reproducible Research. Below is a brief synopsis of the findings, an introduction to the project and which data is used.  
The full analysis of the data can be found in the file `PA2.md`.

## 1. SYNOPSIS

The National Oceanic and Atmospheric Administration (NOAA) maintains a public database for storm events. The data that is collected here displays information on the type of storm and details like location, date, estimates for damage to property as well as the number of human victims of the storm. In this report we investigate which type of events are the most harmful to the population and economically between the period of 1996 and 2011.  

From this analyis it is clear that tornadoes have the highest number of victims, causing the highest number of injuries and the second highest number of fatalities, closely following excessive heat events. Besides tornadoes, other major weather types having a high number of victims were excessive heat events and floods.  
In terms of economic costs however, weather types that occur on a larger scale and have a longer timespan than when compared to tornadoes, seem to have more impact. The leading weather type in terms of costs were floods, having the highest cost in property damage and coming in second in terms of crop damage, being preceded by droughts.  
Furthermore, it appears that the costs for crop damage do not seem to be a major factor in the total costs of damages caused by weather events, as these are majorily governed by costs for property damage. Besides floods, other major weather types having a high economical impact were hurricanes/typhoons and storm surges.

***

## 2. INTRODUCTION

Storms and other severe weather events can cause both public health and economic problems for communities and municipalities. Many severe events can result in fatalities, injuries, and property damage, and preventing such outcomes to the extent possible is a key concern.

This project involves exploring the U.S. National Oceanic and Atmospheric Administration's (NOAA) storm database. This database tracks characteristics of major storms and weather events in the United States, including when and where they occur, as well as estimates of any fatalities, injuries, and property damage.

***

## 3. DATA

The data for this assignment come in the form of a comma-separated-value file compressed via the bzip2 algorithm to reduce its size. You can download the file from the course web site:

* [Storm Data](https://d396qusza40orc.cloudfront.net/repdata%2Fdata%2FStormData.csv.bz2) [47Mb]

There is also some documentation of the database available. Here you will find how some of the variables are constructed/defined:

* [National Weather Service Storm Data Documentation](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2Fpd01016005curr.pdf)
* [National Climatic Data Center Storm Events FAQ](https://d396qusza40orc.cloudfront.net/repdata%2Fpeer2_doc%2FNCDC%20Storm%20Events-FAQ%20Page.pdf)

The events in the database start in the year 1950 and end in November 2011. In the earlier years of the database there are generally fewer events recorded, most likely due to a lack of good records. More recent years should be considered more complete.
