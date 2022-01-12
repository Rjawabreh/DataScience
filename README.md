# DataScience

##READ ME

#This project looks at the publicly available Iris dataset available on SciKitLearn or from downloading via DataHub. The iris dataset consists of 150 rows and 4 columns representing iris flower morphological measurements. This dataset contains measurements from three different species of iris.

#The analysis starts off by importing the data frame and slicing it into three smaller data frames representing the attributes (sepal length, sepal width, petal length and petal width) from each species class (Iris-setosa, Iris-versicolour and Iris-virginica). A row representing the mean, standard deviation and median of each attribute was added to the slices to paint a general picture of the data. An Alexander-Govern statistical test was utilised to illuminate any statistically significant difference between each attribute belonging to the different species slices. 

#Correlation between all the attributes from the entire iris dataset and from each of the slices was calculated and plotted into heat maps to illustrate the correlative relationship between the attributes in a species independent (whole dataset) or dependent manner (slices).
The next logical steps would include a KMeans clustering analysis and accompanying scatter matrix to show if two of the three species are more closely related than the third, which seems to be the case (hypothesis: Iris-versicolour and Iris-virginica).
