# DECISION-TREE-IMPLEMENTATION

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: NARNAMANGALAM BHUMIKA

*INTERN ID*: CT04DG1512

*DOMAIN*: Machine Learning

*DURATION*: 4 weeks

*MENTOR*: NEELA SANTHOSH

DESCRIPTION OF DECISION MAKING TREE

A Decision Tree is a supervised machine learning algorithm used for classification and regression tasks. It mimics human decision-making by breaking down a dataset into smaller subsets while at the same time developing an associated tree structure. The tree consists of decision nodes (conditions on features) and leaf nodes (final decisions or predictions).
In the case of the Iris dataset, the decision tree classifies iris flowers into three species (setosa, versicolor, virginica) based on four features:
•	Sepal length
•	Sepal width
•	Petal length
•	Petal width

TOOLS USED FOR DECISION MAKING TREE CODE

The decision tree classifier in this project was built using:
•	Python: Programming language used for implementation.
•	Scikit-learn (sklearn): A powerful machine learning library in Python used for:
o	Loading the dataset (load_iris)
o	Splitting the dataset (train_test_split)
o	Training the model (DecisionTreeClassifier)
o	Evaluating the model (accuracy_score)
o	Visualizing the model (export_text, plot_tree)
•	Matplotlib: Used for plotting the decision tree graph.
•	Pandas: Used to convert the dataset into a readable table (DataFrame).

IMPLEMENTATION OF DECISION MAKING TREE

The decision tree was implemented using the Scikit-learn library in Python, which provides powerful tools for machine learning tasks. The process began with loading the Iris dataset, a well-known classification dataset containing measurements of three iris flower species. The dataset was split into training and testing subsets to evaluate the model's performance reliably.
A DecisionTreeClassifier was then initialized using the Gini impurity criterion and a maximum depth to prevent overfitting. The model was trained on the training data, allowing it to learn how to classify flowers based on the input features (sepal and petal dimensions). After training, the model was tested on unseen data, and its accuracy was calculated to assess its predictive performance

VISUALISATION OF DECISION MAKING TREE

To interpret the model’s decision-making process, both text-based and graphical visualizations were generated:
•	The textual visualization (export_text) prints out the decision rules in a human-readable form, showing which feature thresholds are used at each split.
•	The graphical visualization (plot_tree) provides an intuitive diagram of the decision tree. Each node displays the feature condition, class distribution, and predicted class. Colored nodes represent the most likely classification at each decision point.

DATASET USED :

The code uses the Iris dataset, a well-known dataset in machine learning containing 150 samples of iris flowers with four features: sepal length, sepal width, petal length, and petal width. The goal is to classify each flower into one of three species: Setosa, Versicolor, or Virginica.

PLATFORM USED

The code can be executed on any platform that supports Python. Common platforms include:
•	Local IDEs: Jupyter Notebook, PyCharm, VS Code
•	Online Platforms: Google Colab, Kaggle Kernels, or any cloud-based Jupyter environment
For beginners, Google Colab is often preferred because it requires no setup and provides free access to GPUs

APPLICATIONS OF DECISION MAKING TREE

•	Medical Diagnosis: Predicting diseases based on symptoms

•	Finance: Credit risk assessment, loan approval systems

•	Marketing: Customer segmentation and targeting

•	Agriculture: Predicting crop yields based on soil and weather data

•	Education: Student performance prediction

CONCLUSION

Decision Trees offer a transparent and intuitive way to model complex decision-making processes. In this project:
•	We successfully trained a Decision Tree model on the Iris dataset.
•	Achieved good prediction accuracy (~92–100% depending on random state and depth).
•	Visualized the model both textually and graphically, which enhances interpretability.
•	This exercise showcases the power of Scikit-learn and Python as effective tools for developing machine learning models, especially when explainability is crucial.

OUTPUT

![Image](https://github.com/user-attachments/assets/446c401e-4e6f-4b4a-9b2a-6472043a5f29)

![Image](https://github.com/user-attachments/assets/d60901ad-6c9c-4f7f-a653-fea2f8eb068e)

![Image](https://github.com/user-attachments/assets/2ace0d87-8d1d-4f7b-98ba-e92abbc77add)

![Image](https://github.com/user-attachments/assets/646e5053-f5ce-4a9c-99a0-f46942c997e8)




