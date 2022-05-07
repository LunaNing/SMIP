# SMIP

==========

The source code of submission8145 for CIKM 2022: Unsupervised Hierarchical Graph Pooling via Substructure-Sensitive Mutual Information Maximization

==========

Dependencies

-Python 3.x
-torch
-tqdm
-networkx

==========

type ./run_SMIP.sh DATANAME FOLD

to run SMIP model on dataset = DATANAME using fold number = FOLD (1-10, corresponds to which fold to use as test data in the cross-validation experiments).

If you set FOLD = 0, e.g., typing "./run_SMIP.sh MUTAG 0", them it will run 10-fold cross validation on MUTAG and report the average accuracy.

==========

check "run_SMIP.sh" for more options
