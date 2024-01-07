# Analyze-International-Debt
Analyze International Debt Statistics Using (PostgreSQL)

In this notebook, I'm going to analyze international debt data collected by The World Bank. The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. We are going to find the answers to questions like: 

- What is the total amount of debt that is owed by the countries listed in the dataset?
- Which country owns the maximum amount of debt and what does that amount look like?
- What is the average amount of debt owed by countries across different debt indicators?

Below is a snapshot of the database you will be working with:

|country_name|country_code|indicator_name                                                    |indicator_code|debt       |
|------------|------------|------------------------------------------------------------------|--------------|-----------|
|Afghanistan |AFG         |"Disbursements on external debt, long-term (DIS, current US$)"    |DT.DIS.DLXF.CD|72894453.7 |
|Afghanistan |AFG         |"Interest payments on external debt, long-term (INT, current US$)"|DT.INT.DLXF.CD|53239440.1 |
|Afghanistan |AFG         |"PPG, bilateral (AMT, current US$)"                               |DT.AMT.BLAT.CD|61739336.9 |
|Afghanistan |AFG         |"PPG, bilateral (DIS, current US$)"                               |DT.DIS.BLAT.CD|49114729.4 |
|Afghanistan |AFG         |"PPG, bilateral (INT, current US$)"                               |DT.INT.BLAT.CD|39903620.1 |
|Afghanistan |AFG         |"PPG, multilateral (AMT, current US$)"                            |DT.AMT.MLAT.CD|39107845   |
|Afghanistan |AFG         |"PPG, multilateral (DIS, current US$)"                            |DT.DIS.MLAT.CD|23779724.3 |
|Afghanistan |AFG         |"PPG, multilateral (INT, current US$)"                            |DT.INT.MLAT.CD|13335820   |
|Afghanistan |AFG         |"PPG, official creditors (AMT, current US$)"                      |DT.AMT.OFFT.CD|100847181.9|
|Afghanistan |AFG         |"PPG, official creditors (DIS, current US$)"                      |DT.DIS.OFFT.CD|72894453.7 |

You will execute SQL queries to answer six questions, as listed in the instructions.
