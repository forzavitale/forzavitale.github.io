---
layout: post
title: Billboard Chart -- Predicting the Hits
---
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Here](https://github.com/forzavitale/DSI-projects/tree/master/PROJECTS/Billboard%20Chart), we examine data on 317 different songs hitting the Billboard Hot 100 chart in the year 2000.  The features explored include: song length, chart entry position, peak chart position, and weeks elapsed from entry until peak.  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Song length is -- perhaps unsurprisingly, due to human attention span and other factors such as commercial demand for radio airtime -- fairly normally-distributed with mean somewhere around four minutes.  This is illustrated in the following histogram:

![histo](../images/billboardlengthhisto.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In terms of genre representation in the Billboard Hot 100, Rock, Country, and Rap are clearly the most popular of those included:

![bar](../images/billboardbar.png)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;There appears to be a linear relationship between the amount of time it takes a song to reach peak position on the chart and the peak position, as we can see in the scatterplot below.  We see that at a 0.05 significance level there appears to be a linear relationship between the amount of time it takes a song to reach its peak position, and that peak position.

![scatter](../images/billboardpeakvtimetopeakscatter.png)

Rock 'n' roll!
