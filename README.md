# Cyber-risk-sector-analysis (R)

## Overview 
This project applies the exploratory data analysis techquies I leanred in my Computational Data Science courses (CDS) this semester at George Mason in R. I examine trends in CSV datasets that are tidy and cleaned. The goal is to display cybersecurity incidents by sector and demonstrate how data-driven analysis can inform my team on where threats populate.

## Skills Learned 

# Tools Used
- RStudio
- Github for practice datasets
- my CDS textbooks on visual plots

## Dataset 
- Incident type
- Sector
- Attack Vector
- Records exposed 

## Visulization 1: Distribution of Incident Severity 
This histogram shows the amount of records/data exposed within the practice dataset.
figures/fig1_distribution_records.png

**My Insight:** Most incidents exposures are relativly low, but a small number of events account for large impacts. Next we will see WHERE the large impacts populate. 
--

## Visualization 2: Incident Severity by Sector 
This box plot compares breach severity across industry sectors. 
figures/fig2_distribution_records.png

**My Insight:** HEALTHCARE and FINANCE show higher median exposure, assuming the need for stronger regulatory cyber practices amongst staff and current established safeguards. 
--

## Visualization 3: Impact by Incident Type
This plot highlights whiich incident types produced the most harm. 
figures/fig3_distribution_records.png

**My Insight:** Ransomware and data breaches result in the highest variability and maximum impact. 
