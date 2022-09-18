## Data Analysis Project -- Indian Start-up Funding Analysis

## Description
This is an analysis of the amount of funding Indian startups have received between 2018 and 2021. The output of the analysis is to help my (hypothetical) team to gain insights into the Indian Startup ecosystem and determine which area of the ecosystem can be funded and would yield the best ROI. The files of the project consist of information on Indian startups that were funded for the years 2018, 2019, 2020 and 2021. These files have been combined, cleaned, stored in csv format and used for further analysis. In these files, informtion on the startup names, funding, sector of operation and year within which they recieved funding are provided.

**Column names and description:**

Company : The name of the company
Founded : The date of company inception/roll out
HeadQuaters : Company's primary location
Sector: Industry of Operation
Amount: The total amount of capital offered to the startup as funding for their business($)
Stage: Stage of financing

## Summary of Data Analyis Method
Firstly, the datasets were viewed in microsoft excel to have an understanding of the nature of the data and understand how the cleaning was to bedone. Particularlyfor the 2018 dataset, manual cleaning was performed to convert all the amounts into dollars. This was to ensure that all data frames had a uniform value for the 'Amount' column whic in our case is the dependent variable. Manual cleaning was also performed on all the data set to ensure uniformity in the 'Sector' and 'Stage columns. The datasets were loaded into Jupyter Notebook where unnecessary informtion such as '.', ',', and ($) were removed. this was to prevent them from obstructing the data analysis process. The individual dataframes were aggregated into a compiled dataframe titled as 'composite', and was used for further cleaning, analysis and visualization.

## Hypothesis
1. Access to a high amount of funding in the Indian Startup Ecosystem is determined by 'Year of founding'.
2. Access to a high amount of funding in the Indian Startup Ecosystem is determined by 'Stage of development'.
3. Access to a high amount of funding in the Indian Startup Ecosystem is determined by'Sector'.
4. Access to a high amount of funding in the Indian Startup Ecosystem is determined by'Location'.

## Conclusion
>In conclusion, it is confirmed that l[Data Set.zip](https://github.com/ebenezeredusei/Indian-Starup-Funding-Analysis/files/9595207/Data.Set.zip)
ocation, stage of develoment, and sector of operation of a startup plays an important role in the amount of funding they are able to acess. Also, it was realized that the Indian startup ecosystem is more friendly towards tech-savvy startups and startups which aim at providing intermediary services
