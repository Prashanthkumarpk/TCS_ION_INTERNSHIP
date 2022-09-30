# TcsIon Rio
Project Synopsis: -
Project Description:
Project Objective & Brief: To develop a deep learning algorithm to detect different types of sentiment contained in a collection of English Sentences or a large paragraph.
1)	Approaches used For Text Classification:
	1.Rule Based Systems
	2. Text Classification Algorithms :
	Some of the most popular machine learning algorithms used for creating text classification models include the naive bayes family of algorithms, support vector machines, Regressions, and deep learning algorithms with CNN and RNN.
	3. Machine Learning based Systems:
2)Performance metrics  included:
	Accuracy
	Precision 
	Recall
	F1 Score

Solution Approach: 
Rule Based Systems:
Rule-based approaches classify text into organized groups by using a set of linguistic rules.
Each rule comprises of a pattern based on semantics and its predicted category.
Machine Learning based Systems:
Text classification based on past observations.
By using training data, the algorithm can learn the different associations between pieces of text and that a particular output (i.e. tags) is expected for a particular input (i.e. text).
Feature extraction: Transforms each text into a numerical representation in the form of a vector. E.g. bag of words [a vector represents the frequency in a predefined dictionary of words ]
The algorithm is fed with training data consisting of feature sets.
Once trained with enough training samples, the machine learning model can begin to make accurate predictions on unseen text with similar feature sets.
Text Classification Algorithms
Some of the most popular machine learning algorithms for creating text classification models include the naive bayes family of algorithms, support vector machines, Regressions, and deep learning algorithms with CNN and RNN. Metrics and Evaluation Cross-validation is a common method to evaluate the performance of a text classifier.

It consists in splitting the training dataset randomly into equal-length sets.
For each set, a text classifier is trained with the remaining samples (e.g. 75% of the samples).
The classifiers make predictions on their respective sets and the results are compared against the human-annotated tags.
With these results, a performance metrics is built, that are useful for a quick assessment on how well a classifier works.

