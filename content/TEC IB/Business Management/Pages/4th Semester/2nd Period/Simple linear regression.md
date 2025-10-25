Simple linear regression is a business toolkit that allows you to statistically make a [[Sales forecasting|sales forecast]] through a line of best fit and casual models. It generally allows businesses to estimate how a dependent variable changes as the independent variable changes.

- **Dependent variable**: The main factor that the business is trying to predict. For example, the dependent variable could be monthly sales.
- **Independent variable**: The factor that the business suspects has an impact on its dependent variable (for example, monthly sales).

# How-to

## Step 1: Scatter diagram

A scatter diagram is a special type of graph designed to show the relationship between two variables. With simple regression analysis, you can use a scatter diagram to see if the data given in terms of X and Y are linearly related.

Suppose a business wants to know the relationship between its online advertising costs and its online sales. The business has been able to get the survey results from its seven online stores for the last year.

| Advertising (in thousands of $) | Online sales (in thousands of $) |
| ------------------------------- | -------------------------------- |
| 1.9                             | 379                              |
| 1.6                             | 335                              |
| 2.4                             | 595                              |
| 4.5                             | 785                              |
| 1.5                             | 350                              |
| 2.7                             | 525                              |
| 1.1                             | 310                              |

With this data, we can create the following scatter diagram.

![[scatter diagram.png|center|500]]

## Step 2: Line of best fit

A scatter diagram shows all the relationships between individual pieces of data for the independent and dependent variables. However, to be useful, a business needs to find a general relationship between the variables that can be used for predictions. A line of best fit will express this general relationship.

You basically draw a line closest to the most number of points in the scatter diagram. It goes roughly through the middle of all the points on the scatter diagram, as seen below.

![[line of best fit.png|center|500]]

We can see from this line that there is a positive relationship between the two variables. Basically, it means that the more money this business invests into advertising, the more sales they get.

## Step 3: Extrapolation

Now that we know that the relationship is positive and we have our line of best fit, we can now forecast into the future. To do this, all we have to do is extend our line of best fit more, since we are assuming that past trends continue, like so.

![[extrapolation.png|center|500]]

# Moving averages

Sometimes when data experiences cycles, they may not be so simple to graph or to see a relationship at all. For instance, consider the following scatter diagram.

![[weird data.png|center|500]]

This looks odd and awkward to relate since the data is so spread out. However, we can take the average every three points in order to 'smooth out' the data, like so.

![[moving averages.png|center|500]]

This looks much better, and we can draw our line of best fit and extrapolate like normal now.

![[moving averages with line of best fit.png|center|500]]