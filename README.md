# Analysing-International-Debt-Statistics
Used SQL to analyse and Internatinal Debt Statistics


Step 1 - The first line of code connects us to the international_debt database where the table international_debt is residing. Let's first SELECT all of the columns from the international_debt table. Also, we'll limit the output to the first ten rows to keep the output clean.

Step 2 - From the first ten rows, we can see the amount of debt owed by Afghanistan in the different debt indicators. But we do not know the number of different countries we have on the table. There are repetitions in the country names because a country is most likely to have debt in more than one debt indicator.

Step 3 - We can see there are a total of 124 countries present on the table. As we saw in the first section, there is a column called indicator_name that briefly specifies the purpose of taking the debt. Just beside that column, there is another column called indicator_code which symbolizes the category of these debts. Knowing about these various debt indicators will help us to understand the areas in which a country can possibly be indebted to.

Step 4 -Let's switch gears from the debt indicators now and find out the total amount of debt (in USD) that is owed by the different countries. This will give us a sense of how the overall economy of the entire world is holding up.

Step 5- "Human beings cannot comprehend very large or very small numbers. It would be useful for us to acknowledge that fact." - Daniel Kahneman. That is more than 3 million million USD, an amount which is really hard for us to fathom.

Now that we have the exact total of the amounts of debt owed by several countries, let's now find out the country that owns the highest amount of debt along with the amount. Note that this debt is the sum of different debts owed by a country across several categories. This will help to understand more about the country in terms of its socio-economic scenarios. We can also find out the category in which the country owns its highest debt. But we will leave that for now.


Step 6 - So, it was China. A more in-depth breakdown of China's debts can be found here.

We now have a brief overview of the dataset and a few of its summary statistics. We already have an idea of the different debt indicators in which the countries owe their debts. We can dig even further to find out on an average how much debt a country owes? This will give us a better sense of the distribution of the amount of debt across different indicators.

Step 7 - We can see that the indicator DT.AMT.DLXF.CD tops the chart of average debt. This category includes repayment of long term debts. Countries take on long-term debt to acquire immediate capital. More information about this category can be found here.
An interesting observation in the above finding is that there is a huge difference in the amounts of the indicators after the second one. This indicates that the first two indicators might be the most severe categories in which the countries owe their debts.We can investigate this a bit more so as to find out which country owes the highest amount of debt in the category of long term debts (DT.AMT.DLXF.CD). Since not all the countries suffer from the same kind of economic disturbances, this finding will allow us to understand that particular country's economic condition a bit more specifically.

Step 8 - China has the highest amount of debt in the long-term debt (DT.AMT.DLXF.CD) category. This is verified by The World Bank. It is often a good idea to verify our analyses like this since it validates that our investigations are correct.

Step 9 - There are a total of six debt indicators in which all the countries listed in our dataset have taken debt. The indicator DT.AMT.DLXF.CD is also there in the list. So, this gives us a clue that all these countries are suffering from a common economic issue. But that is not the end of the story, but just a part of the story.

Let's change tracks from debt_indicators now and focus on the amount of debt again. Let's find out the maximum amount of debt that each country has. With this, we will be in a position to identify the other plausible economic issues a country might be going through.
