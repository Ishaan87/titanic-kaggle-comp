# My first kaggle comp - Titanic dataset
We all know that titanic dataset is the first ever kaggle competition of every beginner - there's nothing new about that!
hence, here I will be documenting my unfiltered approach to it, irrespective of how embarrasing it is.
## First Approach - Decision Trees
I used <b>DecisionTreeClassifier</b> as my first algorithm.<br>
obviously, I first applied preprocessing - in this case, <b>OneHotEncoding</b> for columns 'Sex' and 'Embarked' as they consist of categorical classes. <br>
I removed columns - 'Ticket', 'Name' and 'Cabin' (because I didn't know what could I possibly modify in them to utilize them)

## Second Approach - Adaboost
Yeah, I am using one of the most powerful weapons in the beginning.<br>
In the preprocessing stage I am using:
1) One Hot Encoding - same as before
2) Standard Scaler - Scaling the 'Age' and 'Fare' columns

Okay, so while doing this, I learned that I am very bad at data preprocessing - especially missing values are pain in the ass.