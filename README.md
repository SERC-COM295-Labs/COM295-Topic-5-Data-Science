# COM295 Topic 5 - Data Science

Coding exercises covering Topic 5: Data Science.

This lab is designed to introduce participants to basic data science techniques using Python. The focus will be on data visualization and linear regression, employing widely-used Python libraries to manipulate and analyse data.

At the end of this lab, learners will be able to:

- Utilize Python libraries such as Matplotlib for data visualization to interpret and present data graphically.
- Implement linear regression models using the scikit-learn library to analyze and predict data trends.

The lab aims to provide practical experience with essential tools that are pivotal in data science, equipping participants with the skills necessary for basic data analysis projects.

## Exercise 1 - Data Visualisation

In this exercise, learners will explore different types of visualisation, using the Iris dataset as sample data. The Iris dataset is a classic dataset in the field of data science and machine learning, containing measurements of sepal length, sepal width, petal length, and petal width for three different types of iris flowers (Setosa, Versicolor, and Virginica). You can find more information about the Iris dataset on its [Wikipedia page](https://en.wikipedia.org/wiki/Iris_flower_data_set).

**Objective**: Use Python and its libraries to create visualizations that help understand the Iris dataset's features and their relationships.

**Tools Needed**: Python, Pandas, Matplotlib, and Seaborn libraries. (You can install these libraries using pip if they are not already installed: on the commandline, type `pip install matplotlib seaborn pandas`)

**Dataset**: The Iris dataset is available in seaborn's library dataset collection.

**Tasks**:

1. Load the Dataset
    - Import necessary libraries.
    - Load the Iris dataset using seaborn.

2. Basic Statistics
    - Display basic statistics of the dataset using `.describe()`.

3. Data Visualizations
    - Create the following visualizations. Each should include a title and axis labels where applicable.
        1. Histograms for each feature
            - Plot histograms for each of the four measurements (sepal length, sepal width, petal length, petal width) to explore their distributions.
        2. Box Plots to compare features
            - Create box plots for each measurement grouped by the species of the iris. This will help identify differences between species and see if any features significantly help in distinguishing between species.
        3. Scatter Plot to examine correlations
            - Choose two features, and create a scatter plot to examine the correlation between them. Color the points by iris species to see if species can be distinguished by these two features.
        4. Pair Plot to visualize overall relationships
            - Use seaborn's pairplot to visualize pairwise relationships in the dataset. This plot should also color points by species to help identify relationships not only between the features but also with respect to the species.
        5. Correlation Heatmap
            - Create a heatmap to visualize the correlation matrix of the four measurements. This helps in understanding which measurements are most closely related.

A Jupyter Notebook is provided with the necessary code snippets to get you started. You can use this notebook to complete the tasks.

**Deliverable**: Complete the tasks by filling in the necessary code to generate the required plots. Comment on each plot explaining what insights you can gather about the Iris dataset from each visualization.

This exercise should provide a comprehensive exploration of the Iris dataset, helping understand data visualization's role in data analysis and decision-making.


## Exercise 2 - Linear Regression

In this exercise, using the iris data set, learners will implement a linear regression model to predict the petal length of iris flowers based on their petal width. The goal is to build a linear regression model that can predict the petal length of iris flowers based on their petal width.

**Objective**: Implement a linear regression model using Python's scikit-learn library to predict the petal length of iris flowers based on their petal width.

**Tools Needed**: Python, Pandas, Matplotlib, and Scikit-learn libraries. (You can install these libraries using pip if they are not already installed: on the commandline, type `pip install matplotlib pandas scikit-learn`)

**Dataset**: The Iris dataset is available in seaborn's library dataset collection.

**Tasks**:

1. Load the Dataset
    - Import necessary libraries.
    - Load the Iris dataset using seaborn.

2. Data Visualization
    - Plot the generated data points on a scatter plot to visualize the relationship between the independent variable (x) and the dependent variable (y).

3. Create a Linear Regression Model
    - Use scikit-learn to create a linear regression model and fit it with your data.

4. Evaluate the Model
    - Plot the regression line from the model over the scatter plot of the data.
    - Print the coefficients of the regression, including the slope and intercept, and discuss what they mean in the context of your generated data.

5. Prediction
    - Use the model to make predictions on new data and plot these predictions on the graph.
