
![Logo](https://miro.medium.com/v2/resize:fit:770/1*I84-PCI-kCuSkd7vDt_luQ.png)


# Market Analytics - Customer Segmentation

## Table of Contents
* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
* [Prerequisites](#Prerequisites)
* [Report](#report)





## About the Project

Here we are going to find different shoping groups based on demographics information(age,income) and shoping score to better understand the target group for marketing campaigns.

## Getting Started
Customer Segmentation code is in CustomerSegmentation.ipynb

## Prerequisites
- Python(Pandas, Seaborn, Sklearn, matplotlib)

## Report
- Female around age 20-40 spend the most.
- Female with annual income 50-75 spend the most.
- Female with spending score 35-60 spend the most.
- Median big box means data is concentrated between 25-70 for male and 32-72 for female.
- Spending has a negative correlation with Age. Means older people spend less.
- Considering only **Annual Income** and clustering data to 3 different clusters, the average income in the created clusters will be:
  - 66.7
  - 33.0
  - 99.8
- Considering both **Annual Income** and **Spending Score (1-100)** and clustering data to 5 different clusters, we can see that the ideal clusters are:
  - ![img.png](img.png)
  - Our ideal cluster will be red color one,
    because they have high spending score and high annual income.
  - Another ideal cluster will be green cluster. 
    even though, they have low income but they have high spending score. 
    our guess whould be they spend on game and tech accessories or makeup and young-related items, if their age is not high.
  - Average age for red group is 32 years. 
  - Our guess for group 2 was correct and they are young with mean age around 25 years. 
  - we can arrange campaign around group purple and green. 
  - we can use customer id and dige more into what have been their purchases in order to increase seccess chance of our campaign.

<!---
## License

## Contact

## Acknowledgements

## Feedback
--->















