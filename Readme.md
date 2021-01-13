# Evaluation of Mental Health Classification with Social Media
This study compares several techniques in studying mental health on the social network Reddit. Combinations of different feature selections and classification models are evaluated in terms of accuracy on classifying text as pertaining to Reddit’s communities for depression, anxiety and suicidal ideation. Special consideration is given to whether techniques are likely to understate the severity of cases of suicidal ideation as depression

[Read the Paper](Evaluation_of_Mental_Health_Classification_with_Social_Media.pdf)


## Results
Optimized F1 Scores (Weighted Averages) for Topic Modelling Approach


|                          | Depression vs. SuicideWatch | Depression vs. Anxiety |
|:-------------------------|:----------------------------|:-----------------------|
| Logistic Regression      |             75                |         **77**               |
| SGD                      |             58               |          74              |
| Stacked Generalization\* |             **81**                |     70                   |

</div>

## Citing this paper
ACM Reference Format:
Charles Inwald. 2019. Evaluation of Mental Health Classification with Social Media. 1, 1 (January 2019),9 pages.
