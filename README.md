# Girls-and-Boys
Code For Kaggle Competition: Girls and Boys. 11th in Public Leaderboard, 4th in Private Leaderboard. Stacking Model is proved to be successful in this competition.

Just as a note for future competition. So it is a little messy

The following items are the feature engineerings I have done for this competition.

1. The last column but one was the confusing feature. If you merged it to the features which were fed to the model for predicting, you would get all zeros or the other number. Of course, it was based on Tree-Model.
2. There were lots of pairs of columns were positive correlation, which meant that some of them could be dropped.
3. You could process some operations, such as adding, subtraction or variance, in some pairs of columns, which were useful for creating more features.
