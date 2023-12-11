# Part 4 - Classification Writeup

After completing `a6_part4.py` answer the following questions

## Questions to answer

1. Comment out the StandardScaler and re-run your test. How accurate is the model? Why is that?
The accuracy is 68% because the standardized sacler scales the data by equalizing the range between data points and the standardized the means and standard deviatios of the data set. Without the standard scalar the data is less accurate than with the scalar because of this. 

2. How accurate is the model with the StandardScaler? Is this model accurate enough for the given use case? Explain.
The model is 88% accurate when the standardscaler is included in the code.  It is accurate enough for this case. If the model aimed to make predictions about things that are far more serous, like predcting if someone is chronically ill, this model may not be accurate enough. however, given that this model is for the likelihood that someone will purchase a car, and the overall outcome is far less srious, this model is accurate enough but the data could be more accurate.

3. Looking at the predicted and actual results, how did the model do? Was there a pattern to the inputs that the model was incorrect about?
When looking at the predictions and actual results, the model seemed to to very well of what was printed in the terminal. It's hard to say if there was a pattern, because it is unclear when the model made a mistake.

4. Would a 34 year old Female who makes 56000 a year buy an SUV according to the model? Remember to scale the data before running it through the model.
This prediction is incorrect. This is likely because the 26-40 age demographic varies a lot on who purchases an SUV because the person we tested in the range of ages that are harder to accurately predict, the model wasn't able to accurately guess if she bought an SUV or not.

