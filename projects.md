---
layout: page
title: Projects
permalink: /projects/
main_nav: true
---
___
### Chatbot / CNN intent classifier

***Techs***: Java, Deeplearning4j, Spring, Thymeleaf  
***Fields***: Machine Learning, Chatbots

**Description**: Development of a chatbot software focused on the university community. I was given the chance to develop it at [SINFO--UFRN][sinfo] after finishing 3rd at their Hackathon. The bot was assigned to an internal university chat application and it was able to predict 30+ added intents with a F1 score superior to 95%.

The project was the subject of my [Bachalor's thesis][thesis] (in Portuguese) and it focused more on creating and testing the intent classifier. It used [ApacheNLP][apachenlp]'s entity recognizer and [FastText][fasttext]'s Portuguese word vectors. Also, a web app/module was created with Thymeleaf to manage the database and to check and judge the chatbot outcomes.

___

### NCAA Basketball prediction <small>[\<repository\>](https://github.com/marciojunior159/Projects/tree/master/MLND/%5BFP%5D%20Basketball%20Prediction)</small>

***Techs***: Python, Scikit-Learn, Keras, Pandas, Jupyter Notebook  
***Fields***: Data Science, Machine Learning, Regression, Classification

**Description**: Prediction of NCAA Basketball Tournament results by using season statistics. The project tested the use of several *advanced statistics* as features for the prediction. It was able to classify corretly the final results on 67% of the games from 2010 to 2018.

This was the final project from my Udacity Nanodegree, and it was made in a bit of a rush. Visit the *repository* to check out the report.

___


### Lettering faces <small>[\<repository\>](https://github.com/marciojunior159/Projects/tree/master/lettering)</small>

***Techs***: C++, OpenCV, Qt Creator  
***Fields***: Image Processing

**Description**: Small project made for my *Image Processing* class in mid 2017. It uses images' contours identified using OpenCV to define polygons where words can be inserted, and then it redraws the image with them. It was my first experience with OpenCV and the results were not that good, so I had to tweak it a little in order to at least make it look good. Here's an example I used with Dirk Nowitzki's picture: [before](https://raw.githubusercontent.com/marciojunior159/Projects/master/lettering/imagens/dirk.png) and [after](https://raw.githubusercontent.com/marciojunior159/Projects/master/lettering/imagens/positivo.png).

___

### A*/Greedy searches <small>[\<repository\>](https://github.com/marciojunior159/Projects/tree/master/searches)</small>

***Techs***: C++, QtCreator  
***Fields***: Search algorithms

**Description**: Assignment from my *Applied Artificial Intelligence* class. This program reproduces the Greedy search and the A\* search algorithms using a Qt graphical interface.

___

[sinfo]: https://info.ufrn.br/
[thesis]: https://monografias.ufrn.br/jspui/handle/123456789/8338?locale=en
[apachenlp]: https://opennlp.apache.org/
[fasttext]: https://fasttext.cc/
