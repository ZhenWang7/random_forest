# Decision Tree


Here are a few steps to build a decision tree.

1. Split the dataframe into response variable and explanatory variables. 
2. Select the split criteria.
    1. Gini Impurity - Easier to compute -- Support one firest
    2. Entropy
    3. Log loss.
    
    
3. Start at the root node as parent node. 
4. Split the note at feature x that will minimize the sum of the child node impurity therefore maximize the information gain
4. Split again until the node is pure or stopping rules met.
    * Stopping Rules
        1. Leaf node is pure 
        2. Maximum depth reached
        3. Spliting node does not lead to information gain
    
    
 
 
 
 
 
 ### Resources
[Pratical Deep Learning for Coders](https://course.fast.ai/Lessons/lesson6.html)
[Sklearn](https://github.com/scikit-learn/scikit-learn/blob/35f156a6a3444298f7d3c51ed9928211d6d11a98/sklearn/tree/_classes.py#L40)
[Decision Tree - An introduction](https://github.com/michaeldorner/DecisionTrees)
[Oracle - Scratch Implementations of Major Machine Learning Algorithms](https://github.com/JeremyNixon/oracle)