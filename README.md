# Tree-based-model

I started by loading a cancer dataset that works similarly to heart disease (has binary classes and many features). Then I trained a Decision Tree and checked its accuracy. I also plotted the tree so I can “see” how it makes decisions.

To show how to avoid overfitting, I trained a tree with limited depth and compared its accuracy.

After that, I trained a Random Forest, which is an ensemble of many decision trees, and noticed it usually gives better accuracy because it reduces overfitting.

I looked at feature importances from the Random Forest to see which features matter most. Finally, I used cross-validation to make sure my model performs well on different splits of the data.
