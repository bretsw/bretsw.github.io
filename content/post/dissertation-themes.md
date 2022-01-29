+++
title = "Dissertation Themes"

date = 2020-07-09T00:00:00
lastmod = 2020-10-17T00:00:00
draft = false

tags = ["dissertation", "R", "dataviz", "heatmap", "qualitative", "msu"]
summary = ""

[header]
image = ""
caption = ""

+++

As I've wrapped up numerous cycles of qualitative coding of interview data for my dissertation, *Into the edu-verse: New teachers seeking induction support on social media*, I used `geom_tile()` in **{ggplot2}** to create heatmap plots to help me quickly visualize how thematic codes varied by interview participant.

## Heatmap Comparison of Thematic Codes by Interview Participant

![Themes by participant](/img/dissertation-themes-wordcount-heatmap-sorted.png)

*Note.* Columns have been computationally reordered using principle components analysis (PCA) so that side-by-side columns are more similar than non-adjacent columns. Tile shading represents the number of words a participant spent speaking about a topic relative to how much they discussed other topics, rescaled to 0-100 for comparison between participants.

---

I've shared the code to produce these plots in a [GitHub repository](https://github.com/bretsw/dissertation-themes), and you can also [view on RPubs](https://rpubs.com/bretsw/dissertation-themes) a variety of different heatmaps I created en route to these final plots.
