# challenge14

Step 1: Tune the training algorithm by adjusting the size of the training dataset.

To do so, slice your data into different periods. Rerun the notebook with the updated parameters, and record the results in your README.md file.

Answer the following question: What impact resulted from increasing or decreasing the training window?
The different time periods- the longer the better the results. Although, if you put in more than 100 months, it can not predict the data.

Step 2: Tune the trading algorithm by adjusting the SMA input features.

Adjust one or both of the windows for the algorithm. Rerun the notebook with the updated parameters, and record the results in your README.md file.

Answer the following question: What impact resulted from increasing or decreasing either or both of the SMA windows?
The impact of increasing the SMA window seems to be more accurate. Decreasing make the spread much larger. 

Step 3: Choose the set of parameters that best improved the trading algorithm returns.
The best results were with a more time and longer SMA window. 

** Step 3: Backtest the new model to evaluate its performance.


Answer the following questions: Did this new model perform better or worse than the provided baseline model? Did this new model perform better or worse than your tuned trading algorithm?
THe model performs better with more an increased training window and more months added to the training data. Increasing it too much makes the data invalid. 
