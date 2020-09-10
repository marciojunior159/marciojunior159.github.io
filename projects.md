---
layout: page
title: Projects
permalink: /projects/
main_nav: true
---

Here's a list of some of the projects I've worked with.

___
### &#129302; Chatbot / CNN intent classifier

***Techs***: Java, Deeplearning4j, Spring, Thymeleaf  
***Fields***: Machine Learning, Chatbots, Convolutional Neural Networks

**Description**: Development of a chatbot software focused on the university community. I was given the chance to develop it at [SINFO--UFRN][sinfo] after finishing 3rd at their Hackathon. The bot was assigned to an internal university chat application and it was able to predict 30+ added intents with a F1 score of about 99%.

The project was the subject of my [Bachelor's thesis][thesis] (in Portuguese) and it focused more on creating and testing the intent classifier. It used [ApacheNLP][apachenlp]'s entity recognizer and [FastText][fasttext]'s Portuguese word vectors. The program was developed in Java using IntelliJ and the Spring Framework, and the data used to train the model and give the answer was stored and organised in a PostgreSQL schema. Also, a web app/module was created with Thymeleaf/HTML to manage the database and to check and judge if the chatbot outcomes were correct.

___

### &#128172; Speaking Language Recognition Through Audio Signal Processing  <small>[\<video presentation (Portuguese)\>](https://www.youtube.com/watch?v=lHlbPiWO5dc) [\<draft article\>](https://drive.google.com/file/d/1zcOzVYxWqPe2qYrN_ZTwHy6nOXe3ZPjc/view?usp=sharing)</small>

***Techs***: Python, Keras, Scikit-Learn, Librosa  
***Fields***: Audio Signal Processing, Convolutional Neural Networks, Classification

**Description**: Joint final project for my *Machine Learning* and *Digital Signal Processing* classes in post-graduation. For the first part, I converted a series of audio files from 4 different languages, all collected from the Mozilla Common Voice project, into mel-scaled spectrogram 2d images, and used them to train a Convolutional Neural Network to classify each language on a test set. For the second part, I tried to make the same prediction, but now using numerical data extracted from each audio file and a Random Forests Classifier.
 
The CNN model had a fine result of over 70% precision and recall despite little to no adjustments, and the RFC model was a lot more faulty (less than 60% at every metric) indicating a need for improvement in the data extraction process.

___

### &#127934; Prediction of Outcomes for Tennis Points <small>[\<draft report\>](https://drive.google.com/file/d/1gQ7a2o7xbYRjPJw8GQqC7bRq_8xoJ1gy/view?usp=sharing)</small>

***Techs***: Python, Keras, Detectron   
***Fields***: Recurrent Neural Networks, Object Detection, Mask-RCNN

**Description**: Final project for my *Deep Learning* class in post-graduation. Here I used images from a tennis match shown on TV and manually tagged a few frames indicating the position of the ball, of the players, and the limits of the court. Using Facebook's detectron2, a Mask-RCNN model was trained to predict those elements using the initially tagged frames. The elements found in the model output were stored along creating a time-series, which was then fed to a second model, an RNN built with Keras, to predict if the point had or had not finished at each time step.

___

### &#127936; Prediction of NCAA Basketball Outcomes <small>[\<repository\>](https://github.com/marciojunior159/Projects/tree/master/MLND/%5BFP%5D%20Basketball%20Prediction)</small>

***Techs***: Python, Scikit-Learn, Keras, Pandas, Jupyter Notebook  
***Fields***: Data Science, Machine Learning, Regression, Classification

**Description**: Final project for my Udacity Machine Learning Nanodegree, and honestly made in a bit of a rush. Here I intended to predict NCAA Basketball Tournament results by using regular season statistics. Several *advanced statistics* were tested as features for the prediction, including some extracted from time-series data. The final model was able to correctly predict 67% of games played between 2010 and 2018.

___

### &#128214; Recommending System for Kindle E-books <small>[\<video presentation\>](https://www.youtube.com/watch?v=dYICU9uzd9I)</small>

***Techs***: Python, Keras, Surprise, Pandas  
***Fields***: Recommending Systems, Neural Networks, Data Processing

**Description**: Final project for the IBM Advanced Data Science course I took @ Coursera. Here I used ratings/reviews data from the Amazon Kindle Store (available [here](https://jmcauley.ucsd.edu/data/amazon/)) and tried to find good recommendations for the Amazon users. Two machine learning models were tested for this task: Funk--SVD and a Keras-built neural network, both obtaining something close to 90% precision.

___


### &#128590; Lettering Faces <small>[\<repository\>](https://github.com/marciojunior159/Projects/tree/master/lettering)</small>

***Techs***: C++, OpenCV, Qt Creator  
***Fields***: Image Processing

**Description**: Small project made for my *Image Processing* class in mid 2017. It uses images' contours identified using OpenCV to define polygons where words can be inserted, and then it redraws the image with them. It was my first experience with OpenCV and the results were not that good, so I had to tweak it a little in order to at least make it look good. Here's an example I used with Dirk Nowitzki's picture: [before](https://raw.githubusercontent.com/marciojunior159/Projects/master/lettering/imagens/dirk.png) and [after](https://raw.githubusercontent.com/marciojunior159/Projects/master/lettering/imagens/positivo.png).

___

### A*/Greedy searches &#128269; <small>[\<repository\>](https://github.com/marciojunior159/Projects/tree/master/searches)</small>

***Techs***: C++, QtCreator  
***Fields***: Search algorithms

**Description**: Assignment from my *Applied Artificial Intelligence* class. This program reproduces the Greedy search and the A\* search algorithms using a Qt graphical interface.

___

[sinfo]: https://info.ufrn.br/
[thesis]: https://monografias.ufrn.br/jspui/handle/123456789/8338?locale=en
[apachenlp]: https://opennlp.apache.org/
[fasttext]: https://fasttext.cc/
