---
title: Missingness in meta-analysis
summary: Examining solutions to the missingness issue in meta-analysis
tags:
- statistics
date: "2020-11-24T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://figshare.com/projects/Examining_solutions_to_the_missingness_issue_in_meta-analysis/93065"

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/metaevidence
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Statisticians are often met with a dataset which has missing data across potentially important study characteristics. If the data were complete, effects can be estimated in a controlled way, using techniques analogous to weighted-least squares multiple regression analysis. However, where data are missing and the dataset is incomplete, statisticians have two options: 1) drop the studies which are missing data from the analysis or 2) drop the study characteristics that are missing data. This becomes an untenable solution for many as the missingness often occurs in variables which the methodologist believes may be covariates associated with the magnitude of treatment effect. 

This study forms part of Dr Ciara Keenan’s master’s degree in Biostatistics. Ciara's masters is being supervised by Professor John Newell, School of Mathematics, Statistics and Applied Mathematics in NUI Galway and will be conducted in four stages. 

Stage one will be to complete and share a protocol for a systematic review on the available literature related to missingness in meta-analysis.

Stage two will be to complete a systematic review on the available literature related to missingness in meta-analysis. The information uncovered will be summarised narratively and provide an overview of current understanding and gaps in evidence. 

Stage three will be to develop a shiny app which interested users can access. The app will allow users to simulate missing values in a dataset using three types of missingness: 1) missing at random (MAR) 2) missing completely at random (MCAR) 3) not missing at random (NMAR)

Stage four will be to test various imputation techniques on a simulated dataset. These techniques will be based on the information uncovered in stage two and will be the imputation methods most used in meta-analysis. The objective of this final study is to ascertain which imputation method is most useful for the three types of missingness outlined above.