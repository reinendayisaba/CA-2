# CA-2
**A brief description of the purpose of the program and what it is doing.**

This program uses the Naïve Bayes classification algorithm to train the model with a set of emails that are labelled as either spam or not spam. The total number of emails used is 702, and they’re evenly split between the spam and non-spam categories. The performance of the model – the accuracy of the model – is assessed by using 260 emails and comparing the predicted labels to the true (actual) labels. 


**The Needed libraries and modules**

To be able to run the code, the Numpy library needs to be imported to allow mathematical and scientific computations in Python.

In addition to the above-mentioned libraries, the following modules are also needed in the environment: 
	
•Python’s “OS”: This module needs to be imported to access the functions that make it possible to interact with the operating system. 

•	The “collections” module: This is a built-in module in Python’s Standard Library. It offers specialized container datatypes, which are alternatives to built-in types that include tuples, lists etc. Specifically, this program uses the “Counter” class from the “collections” module, which is used to count the number of times elements/items appear in a list or any other iterable, such as dictionaries.

•	sklearn.naive_bayes: This is a module in the sklearn (scikit-learn) library, which provides tools for predictive data analysis and machine learning. The sklearn.naive_bayes implements Naïve Bayes algorithms, which are supervised learning methods. For this program, the “GaussianNB” class is imported from the module because the Gaussian Naïve Bayes algorithm for classification tasks is the one that’s used. 

•	sklearn.metrics: This module is also part of the sklearn (scikit-learn) library that provides metrics to assess the performance of machine learning algorithms. In this case the “accuracy_score” function is imported from this module in order to calculate the accuracy of the machine learning model.


**How to install and run the code along with datasets to be able to run the program successfully.**

To be able to install and run the code successfully, all the needed libraries and modules need to be installed/imported. Each block of code must also be run individually and in a sequential order (one after another). Moreover, the notebook (.ipynb file) and the two data folders for training (“train-mails”) and testing the model (“test-mails”) have to be saved in the same folder. Not only this, but the path of the data folders must end with './train-mails' and './test-mails'.



**Acknowledgement**

The dataset used in this program was provided by Prof. Arin Brahma. In addition to this, a significant portion of the code used in this program was also provided by Prof. Arin Brahma (GitHub username: ArinB) in a notebook called “CA02_NB_assignment.” The missing parts of the code were completed using the guidance provided under another notebook called “titanic_EDA” that was also provided by Prof. Arin Brahma.


