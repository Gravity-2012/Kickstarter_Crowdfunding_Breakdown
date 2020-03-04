# Kickstarter_Crowdfunding_Breakdown  by Trong Nguyen
Analyzed a database of 4,000 past Kickstarter projects in order to uncover what made certain crowdfunding campaigns successful.

Utizing Excel, I modified and analyzed the data of 4,000 past Kickstarter projects to try and attempt to uncover somemarket trends.

* Used conditional formatting to fill each cell in the `state` column with a different color, depending on whether the associated campaign was successful, failed, or canceled, or is currently live.

  * Created a new column O called `Percent Funded` that used a formula to uncover how much money a campaign made to reach its initial goal.

* Used conditional formatting to fill each cell in the `Percent Funded` column using a three-color scale. The scale starts at 0 and is a dark shade of red, transitioning to green at 100, and blue at 200.

  * Created a new column P called `Average Donation` that used a formula to uncover how much each backer for the project paid on average.

  * Created two new columns, one called `Category` at Q and another called `Sub-Category` at R, which used formulas to split the `Category and Sub-Category` column into two parts.
  
  * Created a new sheet with a pivot table that analyzed my initial worksheet to count how many campaigns were successful, failed, canceled, or are currently live per **category**.

  * Created a stacked column pivot chart that filtered by country based on the table I created.
  
   * Created a new sheet with a pivot table that analyzed my initial sheet to count how many campaigns were successful, failed, or canceled, or are currently live per **sub-category**.

  * Created a stacked column pivot chart that filtered by country and parent-category based on the table I created.
  
  * Created a new sheet with 8 columns:

  * `Goal`
  * `Number Successful`
  * `Number Failed`
  * `Number Canceled`
  * `Total Projects`
  * `Percentage Successful`
  * `Percentage Failed`
  * `Percentage Canceled`

* In the `Goal` column, created 12 rows with the following headers:

  * Less than 1000
  * 1000 to 4999
  * 5000 to 9999
  * 10000 to 14999
  * 15000 to 19999
  * 20000 to 24999
  * 25000 to 29999
  * 30000 to 34999
  * 35000 to 39999
  * 40000 to 44999
  * 45000 to 49999
  * Greater than or equal to 50000
  
  * Using the `COUNTIFS()` formula, counted how many successful, failed, and canceled projects were created with goals within the ranges listed above. Populated the `Number Successful`, `Number Failed`, and `Number Canceled` columns with this data.

* Added up each of the values in the `Number Successful`, `Number Failed`, and `Number Canceled` columns to populate the `Total Projects` column. Then, using a mathematical formula, found the percentage of projects that were successful, failed, or cancelled per goal range.

* Created a line chart that graphed the relationship between a goal's amount and its chances at success, failure, or cancellation.

## Statistical Analysis

Finally, evaluated the number of backers of successful and unsuccessful campaigns statistically. Created a new worksheet in my workbook, and created a column each for the number of backers of successful campaigns and unsuccessful campaigns.

  ![Images/backers01.png](Images/backers01.png)

Used Excel to evaluate the following for successful campaigns, and then for unsuccessful campaigns:

* The mean number of backers.

* The median number of backers.

* The minimum number of backers.

* The maximum number of backers.

* The variance of the number of backers.

* The standard deviation of the number of backers.

Used my data to determine whether the mean or the median summarized the data more meaningfully.
