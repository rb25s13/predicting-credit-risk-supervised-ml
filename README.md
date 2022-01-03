# Predicting Credit Risk with Supervised Machine Learning

                 _._._                       _._._
                _|   |_                     _|   |_
                | ... |_._._._._._._._._._._| ... |
                | ||| |  o NATIONAL BANK o  | ||| |
                | """ |  """    """    """  | """ |
           ())  |[-|-]| [-|-]  [-|-]  [-|-] |[-|-]|  ())
          (())) |     |---------------------|     | (()))
         (())())| """ |  """    """    """  | """ |(())())
         (()))()|[-|-]|  :::   .-"-.   :::  |[-|-]|(()))()
         ()))(()|     | |~|~|  |_|_|  |~|~| |     |()))(()
            ||  |_____|_|_|_|__|_|_|__|_|_|_|_____|  ||
        ~ ~^^ @@@@@@@@@@@@@@/=======\@@@@@@@@@@@@@@ ^^~ ~
            ^~^~                                ~^~^

__________________


<details>
<summary> Tools, Languages, & Libraries Utilized</summary>
<li>Python</li>
<li>Pandas</li>
<li>Pathlib</li>
<li>Sklearn - LogisticRegression, RandomForestClassifier</li>
<li>VS Code</li>
<li>Jupyter Notebook</li>
</details>

__________________



A machine learning model that attempts to predict whether a loan from LendingClub will become high risk or not.

# Credit Risk Evaluator

### Which model will be better? LogisticRegression or RandomForestClassifier?
#### Predictions: 

I predict that the RandomForestClassifier will be a better model due to the data set containing several columns of categorical data.

### Thoughts before scaling data
#### Comparisons from unscaled data: 
The logistic regression model seems to be performing better on the unscaled data. The random forest classifier is performing poorly, possibly due to overfitting.
#### Predictions for scaled data: 
I think the performance of the unscaled data is too poor in the random forest classifier to overcome the deficit of the logistical regression model. I predict both models will perform better after scaling.

### Results
#### Comparisons from scaled data: 
It seems the prediction was incorrect due to random forest classifier actually performing worse after scaling. The logistic regression model performed significantly better after scaling.
#### Results for scaled data: 
The logistic regression model seems to be the way to go meaning my prediction was incorrect. The data set could possibly use some more pre-processing to achieve better results.
