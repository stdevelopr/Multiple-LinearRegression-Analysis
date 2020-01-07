# Multiple regreesion analysis

## Dataset:

The dataset has data collected from New York, California and Florida about 50 business Startups "17 in each state". The variables used in the dataset are Profit, R&D spending, Administration Spending, and Marketing Spending.

## Challenge

Knowing the anual profit of a company and how much it spent in each of these factors:

- State in wich it is settled
- Research and development
- Administration
- Marketing

* Create a model that tells wich types of company yelds best results of profit, based on the given factors. So, given the amount spent in each sector, we would be able to predict the profit.
  After creating the model we should be able to answer questions like:
  \_The company performs better in New York or California?
  \_It is better to invest in companies that spends more on Research and developent or more on marketing?

  ---

### Considerations

Multiple linear regression is an extension of a simple linear regression, where we have more independent variables contributing to the value of the dependent variable.(y= b0 + b1x + b2x2 + ... + bnxn)

- Adding more variables to a multiple regression does not mean it will offer better predictions. To avoid the overfitting problem, the ideia is to pick the best variables to the model.
- When variables are corelated to each other, we have a problem called multicollinearity, and to a better model it should be avoided. The ideal is for all independent variables to be correlated with the dependent variable, but not with each other.

---
# Results:

## After plotting the data and analysing the variables, it was possible to conclude that the best model to predict the profit of the startups should be research and development.
#### *The states in wich state they are settled does not have significant influence.
#### *Althought Research&Delevepment appeared correlated (as research spending increases, so does marketing spending), the most significant and influent variable was R&D, so is the best factor to consider when investing.
#### *Admnistration spend didn't show to be correlated with profit.
