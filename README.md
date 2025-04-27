
# Consumer Psychographic Segmentation

## Overview

[This project](https://wondimuahmed.github.io/psychographic_segmentation/) uses model-based clustering to identify psychographic segments among U.S. leisure
travelers to help a travel tech company personalize offerings and improve marketing strategies.

## Objectives

- Segment consumers based on psychographic charactertics.
- Recommend segment-specific strategies
- Assess if gender and income are associated with segment membership

## Methods & Tools

- *Tech*: R, RMarkdown, tidyverse, plotly, psych, mclust, tidyLPA
- *Analysis*: Factor Analysis, Latent Profile Analysis, Multinomial
  Logistic Regression

## Data

Survey of 502 adults (final n = 298 after quality checks)

## Key Findings

- Three distinct segments emerged:
  - Intentional Explorers – Value planning, culture, sustainability,
    budgeting
  - Practical Travelers – Budget-conscious, moderate planners
  - Spontaneous Explorers – Low-effort, convenience-first travelers
- Gender and income did not predict segment membership—highlighting the
  power of psychographics.

## Recommendations

- Personalize tools by segment
- Tailor messaging
- Simplify UX for spontaneous users

## How to Run

- Place your_data in your working directory
- Install required packages: pacman::p_load(tidyverse, plotly, tidyLPA,
  mclust, psych, nnet, DT)
- Knit the .Rmd file to HTML to view results

## References

A full bibliography of the academic and industry sources that informed
item development and interpretation is provided in the final section of
the report.
