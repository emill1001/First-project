# First-project
Firstly, i wrote a function that loads the data and then renamed the branches according to the task.

In cleaning part I accessed the column names, removed leading and trailing spaces, made the names lowercase and replaced the space character with an underscore so that it is easier to work with the names.

Convertion step. We have string objects in Date column so i converted them into a datetime objects specifying the format, if it can't be converted then just add NaT. Then converted a string Time column unto a Python time objects. Then i also extracted some other useful time periods like month, weekday and hour for further analysis.

During the analysis i firstly found the total sales for each of the product line to determine which products were the most successful on the market.

It turns out that Food and beverages was the best selling category at 56144.8 while Health and beauty finished last at just	49193.7. 

Peak sales were around 7 pm as it is seen from the analysis done by the hour of the day. The exact number is 39699 sales while during the next hour, at 8 pm, the least amount of sales are displayed, only 22969.

Considering the branches, Bazarstore ranked first with 110568 sales but the margin was almost insignificant. Branches and Cities are interchangeable.

January had more sales, 116291, while February had the least 97219.

Saturday had 56120, being the highest sales, while Monday had the least sales, 37899.

According to the heatmap, where i combined weekdays and hours of the day, so on Tuesday and Saturday at 7 pm most sales were made.

I also wrote functions for displaying bar charts and the heatmap with some default values and combined everything into a reusable pipeline.
