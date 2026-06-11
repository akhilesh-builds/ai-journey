1. Conditional probability: 
Conditional probability is probability of occurrence of an event a given that event b has already occurred. defined as p(a|b) = p(a&b)/p(b)

2. Base rate:
The underlying probability of an event in the population, before any specific evidence is considered. Also called the prior.

3. Bayes Theorem:
Bayes theorem basically a way to calculate the conditional probability by using the flipped conditional probability. Formula to flip a conditional probability from one direction to the other, using base rates. P(A|B) = P(B|A) × P(A) / P(B).

4. Independence:
Independence concept states that the occurrance of one event does not depend on the outcome of another event occurred. Like It will rain tomorrow doesnt depend on my coin flip resulted in heads.P(A|B) = P(A) — knowing B happened doesn't change the probability of A.

5. Joint Probability: 
Joint probability is probability of occurance of two events. It is deonted by p(a and b). 
for any event it is defined as p (a and b)  = p(a) * p(b/a)
independent events it becomes p(a and b) = p(a) * p(b), since events are independent p(b/a) = p(b) since event a doesnt impact event b's occurence

6. Normal Distribution:
Bell-shaped, symmetric distribution where we plot random variable on the x axis and we plot no. of occurrences of each random variable value in a given set of data, on Y axis. The histogram that gets generated is same distribution on either side of mean. Another way to say Normal distribution is mean = median = mode. Another way to say is the standard deviation follows the 68-95-99.7 rule.

7. Right-skewed Distribution:
Asymmetric distribution with most data concentrated on the left (low values) and a long tail extending right (rare high values). Mean > Median > Mode.

8. Precision:
Of all the items the model flagged as positive, what fraction is actually positive. True Positives / (True Positives + False Positives). Key metric on imbalanced data — accuracy can be misleading on low base rates, precision tells the truth.

9. Machine Learning: 
Is a programming where instead of manually wiriting rules we give labelled data to computer to learn out of it.

10. Feature: 
Input properties that describes an training record. Its the given input for a ML function.

11. Label: 
Label on training data is the exact outcome based on features. Label from ML model is the predicted outcome based on given features and based on learning from training data.

12. Overfitting: 
Over fitting is a condition where model predicts the correct ourcome/label for the training data only. Once we used the labeled test data, model does not give correct labels. This indicates that model momorized instead of learning.

13. Held-out (test set): 
Data deliberately kept away from the model during training, used only for final evaluation. Prevents the model from being graded on data it already saw, which would mask overfitting.

14. Random_state (reproducibility seed):
A fixed seed for the random number generator. Setting it makes operations like train/test split produce the same result every run, so you can isolate the effect of model changes from the effect of lucky/unlucky data splits.

15. Parameters: 
Values learned during training that define the model. For linear regression with n features: n coefficients (one per feature) plus 1 intercept = n+1 parameters. Neural networks scale this to billions of parameters across multiple stacked equations.
Parameter = what the model learns. Feature = what you feed in.

16. Loss function:
The function a model tries to minimize during training. It measures how wrong the model's predictions are. For linear regression: mean squared error — the average squared difference between predicted and actual values. 

17. Linear Regression: 
Simplest supervised learning algorithm. It finds the best fit line to given features and predicts the outcome in the form of a number. 
Linear regression can only add and subtract scaled features. When the real relationship involves multiplication or curves, the model approximates by using each feature's typical value as a stand-in scaling factor — close, but never exact.

18. r-Squared : 
THis value measures how much of a variance my model could explain give the features provided to my model. Like I gave two features of nightly rates and no of night for a model whcih is predicting total revenue. Revenue varies from 80-800. THen r square will tell us how much of 8-800 variation is explained by two features. If its 1 that means all the variation can be explained by model if its 0 mean none of the variation can be explained. 
"Of all that variation in revenue across bookings — how much of it can my model explain using features like Nights and Rate?"


18. Variance: 
how spread out the data is around its mean. 

19. Feature scaling/Standardization: 
Transforming each feature to have mean 0 and standard deviation 1 (subtract mean, divide by std). For linear regression: doesn't change RMSE or R², but makes coefficients directly comparable — you can now ask 'which feature matters most'. Critical for non-linear algorithms where it actually changes predictions."


20. Data leakage:
Any situation where the model is exposed during training to information it shouldn't have access to at prediction time. Example: fitting the scaler on test data lets the model 'see' test statistics during training. Other examples: using future data to predict past events, including the label as a feature accidentally, leaky cross-validation. The bug pattern: training data and held-out data must stay strictly separated



