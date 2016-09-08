The aim of this project is to use SKLearn tools to predict whether an Enron employee is likely to have committed fraud or not.

The code for this project is split into several python files as follows:

* **poi_id.py** - the main python file which iterates through the various project tasks
* **exploredata.py** - various functions relating to null value and outlier analysis as updates and the creation of new features.
* **feature_selection.py** - initial KBest feature selection code
* **algorithms.py** - code for testing the five different chosen algorithms
* **tester.py** - Udacity file used to test the algorithm results.  Also includes Cross-Validation.

NB: I'm aware that the minmaxscaler has no effect on my final results because the chosen algorithm is a Decision Tree.
