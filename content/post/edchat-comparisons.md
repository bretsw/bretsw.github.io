---
title: "Comparisons in Twitter #Edchat during COVID-19"
date: 2020-07-30
thumbnail: ""
Description: ""
Tags: []
Categories: ["twitter", "dataviz", "heatmap"]
DisableComments: true
---

I am in the midst of two projects looking at how Twitter #Edchat tweets may have been affected by the COVID-19 pandemic. The first project is primarily comparing tweets in Spring 2020 to those in the same timeframe a year earlier. The second project focuses on Spring 2020 but compares tweets from U.K. and U.S. users. I used `geom_tile()` in **{ggplot2}** to create heatmap plots to help me quickly visualize and compare a large number of data points.

## #Edchat: Comparing 2019 to 2020

![Themes by participant](/images/tweets-over-time-comparison-2019-2020.png)

![Themes by participant](/images/hashtag-comparison-big-change.png)

## #Edchat: Comparing U.K. to U.S. tweeters

![Themes by participant](/images/tweets-over-time-comparison-UK-US.png)

#### Top 100 hashtags comparison

![Themes by participant](/images/hashtag-comparison-heatmap-all.png)

#### Top 16 hashtags comparison

![Themes by participant](/images/hashtag-comparison-heatmap.png)

![Themes by participant](/images/hashtag-comparison-scatter.png)

#### Topic models comparison (3 topics per country)

![Themes by participant](/images/topics-UK.png)

![Themes by participant](/images/topics-US.png)

You can view all the output from these projects on RPubs, both the [2019 vs. 2020 project](https://rpubs.com/bretsw/pandemic-edchat) and the [UK vs. US project](https://rpubs.com/bretsw/pandemic-edchat-uk-us).
