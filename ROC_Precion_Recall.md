ROC curve:

receiver operating characteristic curve:

illustrates the performance of a binary classifier system as its discriminationthreshold is varied

True positive rate plotted against False positive rate

meaning:  the area under the curve (often referred to as simply the AUC, or AUROC) is equal to the probability that a classifier will rank a randomly chosen positive instance higher than a randomly chosen negative one

Recall, sensitivity, True Positive rate: TP / P = TP / (TP + FN) : Given a postive number, classify it as True

fall-out or false positive rate (FPR) : FP / N = FP / (FP + TN) 

Precision: TP / TP + FP : Identify a positive, the probability of getting it right

When to Use Precision-recall curve: **Data skewed!!!!**




 Let’s take an example of fraud detection problem where there are 100 frauds out of 2 million samples.
 

Algorithm 1: 90 relevant out of 100 identified

Algorithm 2: 90 relevant out of 1000 identified
 

Evidently,  algorithm 1 is more preferable because it identified less number of false positive. 

In the context of ROC curve,

Algorithm 1: TPR=90/100=0.9, FPR= 10/1,999,900=0.00000500025

Algorithm 2: TPR=90/100=0.9, FPR=910/1,999,900=0.00045502275

The FPR difference is 0.0004500225


For PR, Curve

Algorithm 1: precision=0.9, recall=0.9

Algorithm 2: Precision=90/1000=0.09, recall= 0.9

Precision difference= 0.81

The difference is more apparent in PR curve
