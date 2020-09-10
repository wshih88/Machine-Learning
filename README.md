# Machine-Learning
Using scikit-learn libraries to build and evaluate models we were tasked to evaluate the performance of these models and make a recommendation on whether they should be used to predict credit risk.

## Analysis
Among the methods of testing, determining high-risk clients was very difficult. Based on the LendingClub data, high-risk from all of our testing methods had less than 0.09% precision rating. Of out testing methods for low-risk borrowers, using the Balanced Random Forest Classifier (BRFC) and Easy Ensemble AdaBoost Classifier (EEAC) methods produced testing that had a 0.95 and 0.91 f1 score, respectively. With this, we can confidently state that our testing methods produced results that were both precise and reproduceable. (BRFC precision/recall: 1.00/0.90) (EEAC precision/recall: 1.00/0.94)

I believe that more samples of high-risk borrowers are needed to properly produce a screening method. LendingClub made a business decision to target prime and superprime borrowers over subprime in preparations for a recession per their statement in Q42019 earnings call. Therefore, it is possible that the pool of borrower applications that we see in our sample, may be skewed to low-risk borrowers hence the significant difference in support (EEAC High/Low risk: 101/17104).
