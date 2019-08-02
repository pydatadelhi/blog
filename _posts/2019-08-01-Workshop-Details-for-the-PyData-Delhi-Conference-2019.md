---
layout: post
title:  'Workshop Details for the PyData Delhi Conference 2019'
date:   2019-08-01
categories: python pydata workshop details
permalink: /2019_Workshop-Details/
---

**Date**: 1 August 2019

Greetings!

Glad to know that you will be attending the PyData Delhi conference 2019.If you are planning to attend the workshops, here is a list of prerequisites that we would request you to have ready with you so that you can get the maximum of all that is being delivered at each workshop.

**A.**  **Quantitative Finance with R**
**About the speakers :**

**Harshit Joshi** 

Mr.Joshi is an undergraduate student at Cluster Innovation Centre in Information Technology and Mathematical Innovations.His fields of interest include Computer Vision, NLP and Financial Markets.He uses Numpy, Pandas and Matplotlib extensively and is currently a research intern at DRDO, Data Science Intern at Cronycle Ltd. (UK based startup). He is also a Summer Fellow at Chennai Mathematical Institute working and exploring Mathematical Finance while focusing on intra-day financial data. 

**Vedant Bonde**
Mr. Bonde nurtures a deep interest in the field of mathematical modelling and data visualization.

**Workshop description :**

An introduction to various concepts in mathematical finance, and related mathematics and statistics. The tutorial will brief you about how R helps finance people and will give an insight into their work. Attendees will learn the basics of Finance, Portfolio Optimization, CAPM and more. We will play with real Financial data. This tutorial requires the participants to have a Mathematics background.

**Abstract :** 
The tutorial is divided into various modules, with the first modules lucidly explaining the mathematics and intuition behind the tools used in finance (ex. Random Walks, Geometric Brownian motion) along with the terminology which is common in financial institutions and needed for understanding the upcoming modules. The later modules are related to various concepts and techniques used in the domain of finance like Efficient Frontiers, Asset Pricing Models etc.

**Flow of control of the workshop:** Please visit us at Quantitative Finance and R for a detailed introduction to each section of the workshop.  
>  1. Introduction to R and Finance (10 minutes) 
>  2. The Random Walk Hypothesis and Geometric Brownian motion (20 minutes)
>  3. Efficient Frontier theory (25 Minutes)
>  4. Capital Asset Pricing Model (25 Minutes)
>  5. Exploring Intraday data (BONUS, If time permits)

**Requirements:** 
-  The participants should have taken at least one course in Probability and Statistics.
-  R should be installed with your favourite IDE (we recommend R Studio)
-  Familiarity with R is not required but will be helpful.
-  tseries
-  xts
-  zoo

You can use the following code in the command prompt or R-console to install the packages: install.packages(c("tseries", "xts", “zoo”))

**B.**  **Tips, Tricks and Topics in Text Analysis**

**About the speaker :**
**Bhargav Srinivasa Desikan**

Currently a graduate student at the University of Chicago, Mr.Desikan likes to apply computational techniques to social science problems, mostly working with natural language processing and statistical learning. He has written a book on NLP, published in the Journal of Machine Learning Research, and has spoken at multiple PyDatas/PyCons.

**Workshop Description :**

Not only is there an abundance of textual data, there is also an abundance of tools help analyse this data - and it is tough to choose the right tool for the right task. In this workshop we will be dealing with the entire text analysis process from the preprocessing to its advanced analysis.
We'll start by finding our data, set up a pipeline to clean our text, annotate it, and then have it ready to do some more advanced analysis. We will also spend a while discussing the different ways you can actually create your own dataset for text analysis.
After this, we'll introduce two different approaches of playing with text – one includes approaches such as Topic Modelling, Clustering/Classification, and Deep Learning and the other is a Computational Linguistics approach.

**Abstract :**
The purpose of the tutorial is to introduce the audience to the different sources of textual data available, and give a taste of the different ways we can approach our analysis. It is meant to be more of a breadth than depth survey of the techniques in the field, and we leave the audience to decide which technique would be most useful for their particular use-case.

**Requirements :**
> 1. Jupyter Notebook
> 2. spaCy
> 3. Gensim
> 4. Keras

**C.**  **Advance ML- On Improving Performance of Machine Learning Models by Optimizing Hyper-parameters**
**Anubav Kesari and Tanay Agrawal**

*About the Speakers :*

**Anubav Kesari**
Currently working with Exzeo as Deep Learning Engineer, Mr.Kesari has previously worked with MateLabs as a Machine Learning Intern , where he worked on creating an AutoML platform using Meta Learning, Mateverse. He has been involved in a lot of work centered around the problem of Hyperparameter Optimization and optimized the existing pipeline.

**Tanay Agrawal**
Currently working in Curl Analytics as Deep Learning Researcher, Mr. Agrawal has previously worked as a Deep Learning Intern at Matelabs where he created Meta Algorithms.He is also been a contributor at SymPy. I have previously taken workshop at SFD-SMVDU and also I conduct the session of AI Circle in my College regularly.

**Workshop description :** 

In this tutorial, we'll go step by step, starting with importance of Hyper-parameter optimization. We'll then implement a simple exhaustive search from scratch using for loops and do some exercises. After that we'll try SkLearn's hyper-parameter search algorithms, then we'll compare them with more effective Hyper-Parameter Optimization Algorithm, TPE implemented in Hyperopt.

**Abstract :**

We'll go step by step, starting with what Hyper-parameter optimization is, we'll then implement a simple exhaustive search from scratch and do some exercises, after that we'll try Scikit-Learn's Grid Search and Random Search, we'll compare it with the more effective Hyper-Parameter Optimization Algorithm implemented in Hyperopt Library, TPE. We've included exercise for every part so that, you guys get a good understanding on what you are doing. We'll also go through on how to parallelize the evaluations using MongoDB making the optimization even more effective, and discuss the solution to general difficulties faced while making it work. 

After attending this workshop you will be able to apply Hyper-parameter optimization using better algorithms which decides the hyper-parameters based on previous information instead of just brute force techniques. In short much much efficient model training.

**Requirements:**

A Docker Image will be provided, so that no time is wasted in setting up the environment apart. 

**D.** **Machine Learning Security - The Data Scientist's Guide to Hardening ML Models**
**Arjun Bahuguna**

**About the speaker:**
Mr.Bahuguna is an applied cryptography researcher at Next Tech Lab, with a focus on privacy-enhancing technologies and machine learning security. Recently, he's been involved with applying cryptographic techniques for secure computation to machine learning systems. In the last three years, his research has been awarded with two ACM grants, two university gold medals for original research, and multiple Innovation awards at International hackathons. 

*Workshop description:*

The workshop will aim to provide in depth understanding of Machine Learning security in the following manner - 
> 1. Introduction 
> 2. Real world attacks on Machine Learning Systems 
> 3. Implications on Business Compliance  
> 4. Why do these Attacks occur?
> 5. How do these Attacks affect ML pipelines?
> 6. How to customize your defense for business needs (tradeoffs and tips)?
> 7. Defences 
> 8. Learning to use existing implementations 
> 9. Tips from 3 years of research at Next Tech Lab
The detailed outline of the workshop can be found at : Outline

**Abstract :** Your ML model is insecure. With increased attack incidents on machine learning models (adversarial images, membership inference, model inversion, information reconstruction, data poisoning, etc) it is essential for developers to understand the attack surface of their ML models. We will show how companies like Google & Microsoft are coping with these new threats, and how you can too.

**Requirements:** 
1. Tensorflow 
2. Pytorch 

~ The PyData Delhi Organizing Committee

Written by [**Harshita Diddee**](https://in.linkedin.com/in/harshita-diddee) and [**Khushal Vyas**](https://www.linkedin.com/in/khushal-vyas/)