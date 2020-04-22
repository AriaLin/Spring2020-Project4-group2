# Project 4: Algorithm implementation and evaluation: Collaborative Filtering

### [Project Report](doc/Main.Rmd)

Term: Spring 2020

+ Team 2
+ Project title: Algorithm Implementation and Evaluation (Comparing 
+ Team members
	+ Chairuna, Marsya (mc4813@columbia.edu)  
	+ Duong, Tram (ttd2111@columbia.edu)  
	+ Gong, Saier (sg3772@columbia.edu)  
	+ Lin, Hongshan (hl3353@columbia.edu)  
	+ Wang, Mengchen (mw3371@columbia.edu)  
+ Project summary: In this project, Group 2 implement matrix factorization by focusing on alternating least square algorithms and KNN as post-processing, in which we try to evaluate how regularization will impact the prediction results. We will use RMSE results for both train and test dataset as the basis of our evaluation. The objective of  this project is to produce a prediction of users' movies preference based on the ratings given respective users. We will compare the performance between the following models: 
	+ **Model 1:** Alternating Least Squares (ALS) with Temporal Dynamics (TD) Regularization and K-nearest Neighbors (KNN) Post-processing
	+ **Model 2:** Alternating Least Squares (ALS) with K-nearest Neighbors (KNN) Post-processing
	
+ The structure of the Main report is as follows:
	+ **Section 1:** Model 1 Steps and Output
	+ **Section 2:** Model 2 Steps and Output
	+ **Section 3:** Evaluation and Conclusion 
	
+ **Contribution statement:** All team members contributed in all stages of this project. 
  
  + **Chairuna, Marsya** carried out Model 1 (with regularization). Chairuna assembled, worked on, and organized the README file, Main.HTML, and Main.RMD report files. Chairuna set up the weekly group meetings and actively shared her thoughts during the discussion. 
  
  + **Duong, Tram** took the lead in carrying out Model 2 (without regularization). Duong also took the first cut on creating Model 2 main R Script and Markdown file. Her script serves as the main reference for Model 2 in the Main.HTML and Main.RMD file because her model has the best performance. Duong actively took part and shared her thoughts during our weekly group discussion. 
  
  + **Gong, Saier** took the lead in carrying out Model 1 (with regularization). Gong also took the first cut on creating Model 1 main R Script and Markdown file. Her script serves as the main reference for Model 1 in the Main.HTML and Main.RMD file because her model has the best performance. Duong actively took part and shared her thoughts during our weekly group discussion. 
  
  + **Lin, Hongshan** carried out Model 2 (without regularization). Lin actively took part and shared her thoughts during our weekly group discussion. 

  + **Wang, Mengchen** carried out Model 1 (with regularization). Wang actively shared files and references which greatly helped the team in running the code and completing the project. Wang actively took part and shared her thoughts during our weekly group discussion. 
  
Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
