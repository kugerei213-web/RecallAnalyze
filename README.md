# Project 2: 
Software-Related Recalls — A 100-Fold Increase in 25 Years

## Aim and Findings
In Project 2, I analyzed vehicle recall data from the U.S. NHTSA, which maintains a database of every recall issued since 1949. My hypothesis was that a growing share of recalls is caused by software. To test it, I used an AI-based classifier, and I found a significant increase in software-related recalls.

## Data Sources
| Data | Source | URL |
| --- | --- | --- |
| NHTSA recall records | NHTSA database | [Link](https://www.nhtsa.gov/nhtsa-datasets-and-apis) |

## Overview of the Data Collection Process
1. **General analysis**  
   I downloaded the flat files from the NHTSA website and ran a general analysis with pandas. I had first tried to access the data through the NHTSA API, but the dataset was so large that I ran into many Internal Server Errors, so I changed my approach.
2. **Yearly analysis**  
   I built yearly subsets of the data. With more time or an API key, I could have analyzed every single year, but my resources were limited, so I sampled every fifth year starting from 2000. I then classified the defect summaries into six categories using AI.

## New Skills and Approaches
- **pandas** — general analysis of the CSV data and creation of charts
- **API access** — retrieving recall data (this did not work well)
- **AI classification** — classifying defect summaries into six categories

## Things I Wanted to Do but Could Not
With more time, I would analyze the data for every year instead of every fifth year. That would let me build an area chart and make my website look better, and I believe it would also lead to a stronger analysis.
