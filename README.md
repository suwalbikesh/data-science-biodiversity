# Biodiversity in National Parks: Endangered Species Analysis

## Project Overview

This project analyzes data from the National Parks Service to understand the conservation status of various species across different national parks. Using data from two datasets — `species_info.csv` and `observations.csv` — we explored patterns in endangered species, assessed the significance of differences between species categories, and identified which species are most commonly observed in each park.

## Datasets

* **species\_info.csv**: Contains taxonomy categories, scientific and common names, and conservation statuses of species.
* **observations.csv**: Records the number of observations of each species across multiple parks over the past seven days.

## Goals

* Examine the distribution of conservation statuses among species.
* Determine if certain species categories (e.g., mammals, birds) are more likely to be endangered.
* Evaluate the statistical significance of conservation status differences across categories.
* Identify the species most frequently observed at each national park.
* Provide data-driven recommendations for conservation efforts.

## Methodology

* Data cleaning: Missing conservation statuses were filled as 'No Intervention', and a new binary column indicating protection status was created.
* Exploratory Data Analysis (EDA): Visualized conservation status distributions and proportions across categories using bar charts and stacked bar charts.
* Statistical Testing: Performed chi-square tests to examine if mammals are significantly more endangered than other categories.
* Species Observation Analysis: Merged species and observation data to find the most observed species per park.
* Insights and Recommendations: Interpreted results to provide actionable advice for conservationists.

## Key Findings

* Most species are not currently under conservation intervention, but mammals are significantly more likely to be endangered or threatened.
* Observation frequency does not necessarily correlate with conservation status — common species are not always those most at risk.
* Chi-square tests confirmed statistically significant differences in protection status between mammals and other species categories.
* Conservation efforts should prioritize species based on risk and vulnerability rather than observation counts alone.

## Tools Used

* Python (pandas, matplotlib, seaborn, scipy)
* Jupyter Notebook for analysis and visualization

## How to Use This Project

1. Clone the repository.
2. Ensure the required Python packages are installed (see `requirements.txt`).
3. Run the Jupyter notebook to reproduce the analysis and generate visualizations.
4. Use the findings and charts to inform conservation strategies or for educational purposes.

## Future Work

* Expand the analysis to include more parks and longer observation periods.
* Incorporate additional species characteristics such as habitat or population trends.
* Develop predictive models to identify species at risk before becoming endangered.
