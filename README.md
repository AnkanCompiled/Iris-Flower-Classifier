# Iris-Flower-Classifier

A simple machine learning model that can classify iris flowers into three species based on the length and width of their petals and sepals.

# Install

```bash
pip install -r requirements.txt
```

# Explanation

- load_iris() is a function from sklearn that loads the famous Iris dataset. This dataset contains measurements of iris flowers (sepal and petal length/width) and their species (Setosa, Versicolor, Virginica).
- data.data contains the flower measurements. data.target contains the numeric labels for species:
  - 0 = Setosa
  - 1 = Versicolor
  - 1 = Versicolor
- seaborn.pairplot() creates scatter plots of all combinations of features. hue='species' colors the points by species so we can visually see how the classes are separated.
- n_neighbors=3 means the model looks at the 3 nearest data points to decide the class.
