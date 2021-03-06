---
title: "Final Project: Analyze your data"
linktitle: "3: Final Project"
date: "2021-08-27"
due_date: "2021-12-16"
due_time: "11:59 PM"
toc: true
menu:
  assignment:
    parent: Exercises
    weight: 3
type: docs
editor_options: 
  chunk_output_type: console
---

## Reminder of the class project

The mini-projects and final project are intended to give you the chance to practice the workflows and techniques that we cover in class in the context of a complete analysis. Because each of you are in different stages of collecting your own data and because confronting datasets that aren't yours can help clarify important concepts and design elements, I'm asking you to develop an analysis of data that __isn't yours__. 

The goal here is to have you gain some experience finding spatial data, thinking about an interesting question where the geographic location is (at least partially) important in determining how we might think about the process that gives rise to the data, and developing an analysis and suite of visualizations that help you (and others) better understand that process.

## Final Project

By now you've built a spatial database with a variety of predictors and visualized that data to start to develop some potential hypotheses about how the data relate to each other. The last step is to evaluate your 'hypotheses' (using that term loosely because this is, hopefully, an area outside of your expertise) with a statistical model like the few we've looked at in the last portion of the class. For your final project, I want you to:

* Fit two different kinds of models (e.g. logistic regression and random forest; or, better yet, use the `dismo` vignette and use some of the additional classifiers there; or, better still, read some of the Introduction to Statistical Learning book and use classification approaches described there).

* For each model-type, fit a global model (i.e., a model that contains all of the predictors you've developed) and a reduced model (i.e., a model with only the handful of predictors you imagine to be important based on your visualizations). You should have a total of 4 different model objects.

* Generate the confusion matrix and AUC for each model

* Use k-fold cross-validation (see the vignettes for dismo and Intro to Statistical Learning) to evaluate the preictive accuracy of each model

* Plot the spatial predictions from the best model.

* Submit a knit-able Rmarkdown document that resembles a publishable manuscript. You should have an Introduction that describes the question you are asking, why that interests you, and the hypothses you intend to evaluate (1-2 paragraphs, max). You don't have to have an exhaustive literature search (or any citations at all, really) just set up the analysis you are hoping to do. You should have a methods section that describes your approach to manipulating the data (with code chunks) and justifies assumptions or modifications you made along the way. You should be able to put the plots of your results, AUC and confusion matrices, and Cross-validation results in a Results section. Finally, you should close with an interpretation of your results that includes some reflection on which model was the best for your question and why (2-3 paragraphs, max).
