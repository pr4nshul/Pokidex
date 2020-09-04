# Pokidex

A machine learning program that uses Support Vector Machines for image classification of various Pokemons.

## Getting Started

What is SVM?

The objective of the support vector machine algorithm is to find a hyperplane in an N-dimensional space(N — the number of features) that distinctly classifies the data points.


![Possible hyperplanes](/Pokidex-images/SVM-1.png)




To separate the two classes of data points, there are many possible hyperplanes that could be chosen. Our objective is to find a plane that has the maximum margin, i.e the maximum distance between data points of both classes. Maximizing the margin distance provides some reinforcement so that future data points can be classified with more confidence.
Hyperplanes and Support Vectors


Hyperplanes are decision boundaries that help classify the data points. Data points falling on either side of the hyperplane can be attributed to different classes. Also, the dimension of the hyperplane depends upon the number of features. If the number of input features is 2, then the hyperplane is just a line. If the number of input features is 3, then the hyperplane becomes a two-dimensional plane. It becomes difficult to imagine when the number of features exceeds 3.

![Support Vectors](/Pokidex-images/SVM2.jpg)


Support vectors are data points that are closer to the hyperplane and influence the position and orientation of the hyperplane. Using these support vectors, we maximize the margin of the classifier. Deleting the support vectors will change the position of the hyperplane. These are the points that help us build our SVM.

## Dependencies
- Python
- MatPlotLib
- Numpy
- Pandas
- Sklearn
- OpenCV
## Overview of project


![Taking a random dataset](/Pokidex-images/Example1.png)
	-Taking a random dataset

![SVM class implementation](/Pokidex-images/SVMclass.png)
	- SVM class implementation

![Results after applying SVM](/Pokidex-images/Example-1-SVM.png)
	- Results after applying SVM

![Visualizing loss](/Pokidex-images/Loss.png)
	- Visualizing Loss

![One vs all function for 3 classes](/Pokidex-images/OnevAll.png)
	- One vs all function for 3 classes

![Visualizing Pikachu](/Pokidex-images/Pikachu.png)


![Visualizing Charmander](/Pokidex-images/Charmander.png)

	- Visualizing images from data dictionary with results on the top.

## Contribution 
* Refer ![Contribution.md](https://github.com/pr4nshul/Pokidex/blob/master/Contribution.md)

