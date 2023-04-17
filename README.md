# credit-risk-classification

## **Analysis Overview**
The goal of this analysis is to assess the suitability of a learning model to evaluate the creditworthiness of potential borrowers using machine learning models.

## **Results**
Original data:
- Accuracy: 99.18%
- Healthy loan precision: 100%
- Healthy loan recall: 99%
- High-rsik loan precision: 85%
- High-risk loan recall: 91%

Oversampled data:
- Accuracy: 99.38%
- Healthy loan precision: 100%
- Healthy loan recall: 99%
- High-risk loan precision: 84%
- High-risk loan recall: 99%

## **Summary**
Original data: The sample size of the high-risk loans are significantly lower than the healthy loans. However, based on the data we have, the precision of the healthy loans are clearly better than those of the high-risk loans. The model does do an adequate job at predicting both, however.

Oversampled data: Recall rose in high-risk loans up to 99%, compared to 91% originally. Additionally, f1-scores rose in the high-risk loans. However, precision decreased by 1%. Overall, the healthy loans performed very similarly to how they did originally, but there was an obvious improvement in how high-risk loans performed in the new model.

Recommendation: The oversampled data model is better in this case as it has improved scores nearly all around. The recall rising from 91% to 99% in high-risk loans is the most important factor to me, as the healthy loans didn't show much of a difference between the models and the precision in high-risk loans only decreased by 1 point. I'd recommend the second model over the first, but the lacking sample size in high-risk loans remains an issue.
