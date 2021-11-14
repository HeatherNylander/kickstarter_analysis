# Kickstarting with Excel

<!--Overview of Project -->
## Analyzing Kickstarter data based on their launch dates and their funding goals.

<!--Purpose -->
### Louise wants to know the best launch date for a play Kickstarter and she would like to compare her funding goal to other plays and whether they were successful or not.

## Analysis and Challenges

<!--Analysis of Outcomes Based on Launch Date -->
### I created a pivot table filtered by "Parent Category" and "years". I then filtered the parent category so that only "Theater" Kickstarters would be shown. The filtered pivot table can be seen below: 
<!-- Enter Pivot Table here -->

![Launch_Date_Pivot](https://user-images.githubusercontent.com/92553327/141666210-3c79dff5-05ad-4e10-a8f1-683091ffd760.png)

This pivot table shows the number of failed, successful, canceled, and live theater Kickstarter campaigns. Here is a visualization of the pivot table broken down into months: 
<!-- Enter Graph here -->

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/92553327/141666229-248ec68b-de1e-4553-bbbd-172d929ef274.png)


<!--Analysis of Outcomes Based on Goals -->
### A new sheet called "Outcomes Based on Goals" was created to hold data finding the number of successful, canceled, and failed projects in the "plays" subcategory based on goal amount. That data was then used to find the total number of projects in each category and finally, a calculation was done to display the percentage of projects in each goal category that were either successful, failed, or canceled. Here is a visualization of that data. 
<!-- Enter Graph here -->

![Outcomes_vs_Goals](https://user-images.githubusercontent.com/92553327/141666237-c0f03b95-f885-4e2d-a6f7-81745ec34938.png)

<!--Challenges and Difficulties Encountered -->

### A challenge one might encounter with dataset is that there are multiple currencies shown. In this project, we only looked at campaigns that used the Great Britain Pound. However, if we need to utilize this data to look at multiple countries in the future, an added column would be required to account for exchange rates between currencies. 

## Results

<!--What are two conclusions you can draw about the Outcomes based on Launch Date? -->
- The best time to launch a theater campaign appears to be May, while June and July may also be good options. December has a similar number of successful and failed campaigns so we can conclude that December would not be a good month to launch. 

<!--What can you conclude about the Outcomes based on Goals? -->
- For play Kickstarter campaigns, it appears that campaigns with a goal between $0 and $14999, and $35000 to $44999 had more successful camaigns than failed ones. Between $15000 and $34999, and above $45000 were more likely to fail.

<!--What are some limitations of this dataset? -->
- One limitation of the dataset is that the currency is stated but the goal and pledged amounts have not been adjusted to compare different countries while considering exchange rates. Another limitation is that there is no in depth data to show location beyond the country. Campaigns in different counties may have different outcomes.

<!--What are some other possible tables and/or graphs that we could create? -->
- We have visualized outcomes based on the month in which a campaign was started without looking into the year in which the campaign was launched. We could create separate visualizations broken down by month for each particular year to verify that there is a trend within the month launch date, or to see if year was more important. 



