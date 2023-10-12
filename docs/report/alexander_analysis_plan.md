---
title: "Analysis Plan for Malcomb Reproduction Study"
author: "Sydney Alexander"
output: html_document
date: "2023-10-12"
---

# description of modifications with rationale

I will change the visualization of Malcomb's Vulnerability to CLimate Change map so that it instead shows risk for TAs.
I will do this by using an **aggregate** function in order to calculate mean values of vulnerability from the raster for each TA.
The first two maps visualizing resilience scores looked at TAs, and it makes sense to keep that consistent across all the maps of the study.
The vulnerability map was originally a raster because original layers used to calculate vulnerability were also rasters.
It would be easier for stakeholders or policymakers to allocate funding or assess risk in areas by breaking up the raster into TA zones. 


# plans for visualization and comparing/interpreting results 
I will visualize this result by creating a new map showing the mean vulnerability scores for each TA. Rather than having the scale/data be continuous, I will break it up into ranges, which makes more sense because this is not continuous data. 