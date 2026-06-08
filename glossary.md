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

9. Machine Learning: Is a programming where instead of manually wiriting rules we give labelled data to computer to learn out of it.

10. Feature: Input properties that describes an training record. Its the given input for a ML function.

11. Label: Label on training data is the exact outcome based on features. Label from ML model is the predicted outcome based on given features and based on learning from training data.

12. Overfitting: Over fitting is a condition where model predicts the correct ourcome/label for the training data only. Once we used the labeled test data, model does not give correct labels. This indicates that model momorized instead of learning.