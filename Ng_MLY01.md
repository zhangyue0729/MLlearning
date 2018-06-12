Origin content via Andrew Ng.
Note by Z.
## Setting dev & test set

* Training set -- for training algo.
* Dev set -- for tune parameters & select features.
* Test set -- just for evaluate performance.

**These sets direct the most important changes of your project.**

Dev & set set should have same distribution.

Dev set should big enough to find difference from various algos, so to test set.

While in big data area, even the numbers of total examples increased, the fraction of test & dev set are shrinked.

Single metric in optimizing.  
* &emsp;&emsp;Satisficing metric: must 
* &emsp;&emsp;Optimixing metric: better

Iterate quickly to measure the model performance frequently.

Choose test & dev set and metrics first to determine the aim of team.

**It is better to come up with something imperfect and get going quickly, rather than overthink this.**

Make sure that your dev & test set from same distribution even if it is different from training set.


## Basic Error Analysis
**Don't start off trying build perfect system. Build your basic system quickly, then iterate.**
If you want to modify your model, you'd better analysis the accont that the factor takes to make sure that this change will make sense obviously.
