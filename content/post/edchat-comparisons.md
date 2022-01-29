+++
title = "Comparisons in Twitter #Edchat during COVID-19"

date = 2020-07-01T00:00:00
lastmod = 2020-07-30T00:00:00
draft = false

tags = ["dissertation", "msu"]
summary = ""

[header]
image = ""
caption = ""

[[gallery_item]]
album = ""
image = ""
caption = ""

[[gallery_item]]
album = ""
image = ""
caption = ""

[[gallery_item]]
album = ""
image = ""
caption = ""

# **Bold**
# *Italic*
# `Code`
# ~~strikethrough~~

# ```bash
# Code block
# ```
        
# [Hyperlink text](https://themes.gohugo.io/theme/academic/)
# {{< gallery >}}

# - Unordered list item 1
# - Unordered list item 2

# ## Header 2
# ### Header 3

# 1. Ordered list item 1
#    * Indented list item
# 2. Ordered list item 2

+++

I am in the midst of two projects looking at how Twitter #Edchat tweets may have been affected by the COVID-19 pandemic. The first project is primarily comparing tweets in Spring 2020 to those in the same timeframe a year earlier. The second project focuses on Spring 2020 but compares tweets from U.K. and U.S. users. I used `geom_tile()` in **{ggplot2}** to create heatmap plots to help me quickly visualize and compare a large number of data points.

## #Edchat: Comparing 2019 to 2020

![Themes by participant](/img/tweets-over-time-comparison-2019-2020.png)

![Themes by participant](/img/hashtag-comparison-big-change.png
)

## #Edchat: Comparing U.K. to U.S. tweeters

![Themes by participant](/img/tweets-over-time-comparison-UK-US.png)

#### Top 100 hashtags comparison

![Themes by participant](/img/hashtag-comparison-heatmap-all.png)

#### Top 16 hashtags comparison

![Themes by participant](/img/hashtag-comparison-heatmap.png)

![Themes by participant](/img/hashtag-comparison-scatter.png)

#### Topic models comparison (3 topics per country)

![Themes by participant](/img/topics-UK.png)

![Themes by participant](/img/topics-US.png)

![Themes by participant](/img/topics-UK-US.png)

You can view all the output from these projects on RPubs, both the [2019 vs. 2020 project](https://rpubs.com/bretsw/pandemic-edchat) and the [UK vs. US project](https://rpubs.com/bretsw/pandemic-edchat-uk-us).
