# tableau-challenge

## Summary

This purpose of this project was to aggregate the data found in the Citi Bike trip history logs and create visualisations using Tableau Public. 

History log data for the 2020/2021 financial year was collected, aggregated and cleaned using Jupyter Notebook. However, the raw and cleaned csv data files were excluded from this repository due to their large file size totaling 9 GB. The Jupyter Notebook files can be found in the main folder: data_cleaning_small.ipynb was used as a test run in Tableau only comprising 3 months of data, data_cleaning.ipynb includes the full 2020/2021 financial year.

The final Tableau workbook can be found here https://public.tableau.com/app/profile/ivana.stopka/viz/tableau-challenge_16407777288320/CitiBikes2021Q1Q2?publish=yes

Important Note: Due to Tableau Public's row limit of 15 million, the full 2020/2021 financial year could not be imported and analysed. Instead, a subset containing the first 2 quarters of 2021 was used.

## Exploration

The following phenomena were explored:
- Where the most popular citibike ride destination is in New York - found to be Union Square Greenmarket
- Seasonal variability in ridership (total, member, casual) - 80% drop in total number of rides from Summer (June) to Winter (February). Members had a significantly smaller drop compared to Causal riders as expected with a quarter of Members continuing to ride in the the coldest month (February). 
- Most popular times of the day to begin and end a ride - I expected mornings for the start and afternoons for the end but interestingly both start and stop were most popular during the period 5-6pm. Short distance riders for post-work dinner/drinks suspected.
- What is the longest ride duration and where do people go for their long rides - longest ride duration was found to be just under 800 mins (13 hours) and the top destinations for the long rides were Central Park. Suspected the long riders were day trippers/tourists with Central Park being a popular tourist destination.

## Tools Used

Python, Pandas (Jupyter Notebook) and Tableau Public

## Visualization

The story created in Tableau looks as follows:

![image](https://user-images.githubusercontent.com/86386401/147805471-a33b96fd-d984-4bb8-9b4e-3f5edd23e99b.png)

![image](https://user-images.githubusercontent.com/86386401/147805489-5dfed831-88a4-4085-8fd2-ed52cbdb7f40.png)

![image](https://user-images.githubusercontent.com/86386401/147805506-5d4fd3d6-6917-447a-b4f6-88a39ee64745.png)

![image](https://user-images.githubusercontent.com/86386401/147805552-57a6ad97-034a-456a-b4bf-ed7b84651aaf.png)

![image](https://user-images.githubusercontent.com/86386401/147805559-d1c6f09e-e15b-4b06-9860-42ce6329b51a.png)

