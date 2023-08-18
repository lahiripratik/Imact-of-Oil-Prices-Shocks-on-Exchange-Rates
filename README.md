# Impact of Oil Prices Shocks on Exchange Rates

In this project, I attempted to study multivariate time series analysis using Bayesian inference. 
I have made an attempt to explain the BVAR model employed in this study right from scratch below.

![Projects-5](https://github.com/lahiripratik/Imact-of-Oil-Prices-Shocks-on-Exchange-Rates/assets/84749230/ed29bfd9-0ffa-4f49-a2fc-d3385c2b2a2f)

Now that we have understood what the BVAR is, let us jump into the equations and coefficients I have tried to predict in the analysis.
### The supply side shocks are represented by changed in the variable world oil production and the demand side shocks have been represented by changes in global economic activity.

![Projects-6 2](https://github.com/lahiripratik/Imact-of-Oil-Prices-Shocks-on-Exchange-Rates/assets/84749230/dae32959-447f-4571-b36a-d7b4bbfb3e64)

## The logic and math involved behind training the model

![Projects-7](https://github.com/lahiripratik/Imact-of-Oil-Prices-Shocks-on-Exchange-Rates/assets/84749230/70f3936a-70b0-4ae7-b24a-f14d7f5b9c39)

## The final distribution plots for the coeffecients after training the dataset.
We ran our model over two Markov Chains (similar to epochs), the dotted curves show the results after the first chain and the solid curves show final results after the second chain.
![image](https://github.com/lahiripratik/Imact-of-Oil-Prices-Shocks-on-Exchange-Rates/assets/84749230/c23f2bfc-10d7-472f-bf30-46cd63f58810)

## The correlations after training the model. 
The correlations actually talk about how much of the deviations in the value of a particular variable are explained by the other variable. For each dependant variable, we can see the impact of 24 other independant variables on it, and their impact. The farther it is from the 0 value, the more significant its impact was found to be.

![image](https://github.com/lahiripratik/Imact-of-Oil-Prices-Shocks-on-Exchange-Rates/assets/84749230/5a6abc92-56f2-457c-827d-aca4e522c08a)

## Finally running the model over the testing data with the final state of the coefeccient distributions.

![image](https://github.com/lahiripratik/Imact-of-Oil-Prices-Shocks-on-Exchange-Rates/assets/84749230/1eff10f4-82a9-4290-9b53-40462dc0e03b)


