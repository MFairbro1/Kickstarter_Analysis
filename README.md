# kickstarter-analysis
Analysis of Kickstarter data to uncover trends

## Louise wants to know how well other fundraising campaigns have done based on their launch dates. She is particularly interested in how campaigns from the theater category (musical theater, plays, etc.) performed in relation to their fundraising goals.

### The results of this inquiry will allow her to determine a launch date for her own theater campaign that will grant her the greatest chance of success. Looking at fundraising goals of other theater projects will also allow her to set realistic fundraising goals.

## In order to conduct an analysis of the outcomes of theater fundraising campaigns, I made use of pivot tables and line charts to track performance in a continuous fashion.

### When exploring outcomes of theater campaigns based on launch date, I created a pivot table with campaign outcomes for the columns and launch dates by month for the rows. For each month, the count of successful, failed, and canceled outcomes were listed. I filtered the table by year and fundraising category, specifically focusing on the "theater" category. I then created a line chart to display the trends of success and failure based on launch date.

### When exploring outcomes based on fundraising goals I created a table with several goal ranges in the first column. I then created columns with the number of successful, failed, and canceled campaigns (specifically for the "plays" subcategory of theater) that fell into those various ranges. I made another column with the sum total of all outcomes for each range which I then used, in combination with the other columns, to create new columns giving percentages of successful, failed, and canceled projects for each goal range. Finally, I created a line chart with the percentages plotted against the goal ranges.

### While not a difficult task, it would be potentially easy to make a mistake or omission with the filters used in the COUNTIFS function while populating the columns containing the number of successful, failed, and canceled projects. These would need to be double-checked to avoid any such mistakes.

## Results:

### From the analysis of outcomes based on launch date we can conclude that by far, the months of May and June yield the most successful fundraising campaigns. Additionally, we can see that the least appealing month to launch a campaign is in December, as it yields the least amount of success.

### Looking at outcomes based on goals, we can see that the most successful campaigns are those with goals under $5000 or those with goals between $35000 and $45000.

### One of the limitations of this particular dataset is a lack of information regarding incentives for backers. Being able to compare backer rewards and incentives (if there are any) for different projects could give us a better idea of how to create successful campaigns.

### It could be worthwhile to create a table with the average number of backers for campaigns in each goal range. Perhaps there is a correlation between the number of backers and the success of a fundraising campaign. It could also be helpful to look at the average donation amounts for the more successful campaigns. Plotting the average number of backers against goal ranges could also give insight into why the second most successful range is $35000-$45000.
