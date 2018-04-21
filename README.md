Project 2018 (Programming and Scripting)
The Iris Data set is perhaps the best-known data set to be found in the classification literature. The aim is to classify iris flowers among three species (setosa, versicolor or virginica) from measurements of length and width of sepals and petals.The data set contains 3 classes of 50 instances each, where each class refers to a type of iris plant. The central goal here is to design a model which makes good classifications for new data, in other words one which exhibits good generalization. The next figure is a picture of an iris flower of the versicolor specie.
The Iris flower data set or Fisher's Iris data set is a multivariate data set introduced by the British statistician and biologist Ronald Fisher in his 1936 paper The use of multiple measurements in taxonomic problems as an example of linear discriminant analysis. It is sometimes called Anderson's Iris data set because Edgar Anderson collected the data to quantify the morphologic variation of Iris flowers of three related species. Two of the three species were collected in the Gaspé Peninsula "all from the same pasture, and picked on the same day and measured at the same time by the same person with the same apparatus".
The data set consists of 50 samples from each of three species of Iris (Iris setosa, Iris virginica and Iris versicolor). Four features were measured from each sample: the length and the width of the sepals and petals, in centimetres. Based on the combination of these four features, Fisher developed a linear discriminant model to distinguish the species from each other. A simple function that, given the four measurements, classified a flower correctly. This was the beginning of creating “predictors” in order to try to make a more educated guess on a record in a dataset. 
The Iris data set, a small, well-understood and known data set, consists of the measurements of four attributes of 150 iris flowers from three types of irises. The typical task for the Iris data set is to classify the type of iris based on the measurements. It is one of the most analyzed data sets in statistics, data mining, and multivariate visualization. It was first published by R. A. Fisher in 1936 [1] and is widely available (our copy came from StatLib at CMU (http://lib.stat.cmu.edu)). The file is in CSV format, which can be imported to Excel and other programs.
The data dimensions are as follows:
1.	sepal length in cm;
2.	sepal width in cm;
3.	petal length in cm;
4.	petal width in cm;
5.	class:
	Iris Setosa
	Iris Versicolour
	Iris Virginica
The Iris dataset is deservedly widely used throughout statistical science, especially for illustrating various problems in statistical graphics, multivariate statistics and machine learning. Containing 150 observations, it is small but not trivial. The task it poses of discriminating between three species of Iris from measurements of their petals and sepals is simple but challenging. The data are real data, but apparently of good quality. In principle and in practice, test datasets could be synthetic and that might be necessary or useful to make a point. Nevertheless, few people object to real data. Using a few famous datasets is one of the traditions we hand down, such as telling each new generation that Student worked for Guinness or that many famous statisticians fell out with each other. That may sound like inertia, but in comparing methods old and new, and in evaluating any method, it is often considered helpful to try them out on known datasets, thus maintaining some continuity in how we assess methods. Last, but not least, the Iris dataset can be enjoyably coupled with pictures of the flowers concerned.
Data set
The first step is to prepare the data set, which is the source of information for the classification problem. The file irisflowers.csv contains the data for this example in comma separated values (CSV) format. Once the data file is ready, we import it in Neural Designer using the "Import data file" wizard.
Using the information I researched the websites for python codes and was able to sort each category of data and find the minimum and maximum values (https://github.com/Anoopabraham126/Maximum-Minimum-values/blob/master/max-min%20values). Iris virginica had the longest sepal and petal length and the widest petal while Iris setosa had the widest petal.When calculating the minimum value it was seen that the Iris setosa had the smallest petal length and width as well had the shortest sepal length and width.
	Iris setosa	Iris versicolor	Iris virginica
	Sepal length	Sepal width	Petal length	Petal width	Sepal length	Sepal width	Petal length	Petal width	Sepal length	Sepal width	Petal length	Petal width
												
Min value	4.3	2.3	1	0.1	4.9	2.0	3	1	4.9	2.2	4.5	1.4
Max value	5.8	4.4	1.9	0.6	7	3.4	5.1	1.8	7.9	3.8	6.9	2.5

The python codes also enabled to calculate the average value of each category of each flowers (https://github.com/Anoopabraham126/average-of-a-list-of-numbers/blob/master/average)

	Iris setosa	Iris versicolor	Iris virginica
	Sepal length	Sepal width	Petal length	Petal width	Sepal length	Sepal width	Petal length	Petal width	Sepal length	Sepal width	Petal length	Petal width
												
Average	5.05	3.42	1.46	0.24	5.94	2.77	4.26	1.33	6.59	2.97	5.55	2.03

The above table summarises the outputs. It is seen that on an average Iris virginica had the longest sepal and petal as well as the widest petal while Iris setosa had the widest sepal.
Conclusion
The above project explains what is Iris data set, its importance and use in today’s world. Literature show that this data set I the most simple data set and can be used to generate codes.The project also explains the findings using python codes to obtain the maximum, minimum and average value. 


References
1.	https://en.wikipedia.org/wiki/Iris_flower_data_set
2.	https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/iris.html
3.	https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/iris.html
4.	https://stats.stackexchange.com/questions/74776/what-aspects-of-the-iris-data-set-make-it-so-successful-as-an-example-teaching
5.	https://www.neuraldesigner.com/learning/examples/iris_flowers_classification
6.	https://github.com/Anoopabraham126/average-of-a-list-of-numbers/blob/master/average
7.	https://github.com/Anoopabraham126/Maximum-Minimum-values/blob/master/max-min%20values

