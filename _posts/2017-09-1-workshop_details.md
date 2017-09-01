---
layout: post
title:  'PyData Delhi Conference 2017: An Introduction'
date:   2017-07-11
categories: python pydata conference
permalink: /conf_introduction/
---
You can find the details and prerequisite for each workshop below:

##Machine Learning as a Service
####*Anand Chitipothu*

Anand has been crafting beautiful software since a decade and half. He’s now building a data science platform, rorodata, which he recently co-founded. He regularly conducts advanced programming courses through Pipal Academy. He is co-author of web.py, a micro web framework in Python. He has worked at Strand Life Sciences and Internet Archive.

**Workshop abstract:**
One of the common pain points that we have come across in big organizations is the last-mile delivery of data science applications.

In this workshop, you would learn how to build a seamless end-to-end data driven application - Data Exploration, Machine Learning Model, RESTful API and Web Application - to solve a business prediction problem.

**Software Requirements:**
We will be using Python data stack for the workshop. Please install Anaconda for Python 3.5 or 3.6 for the workshop.

Install the required packages using conda.

conda install numpy pandas matplotlib seaborn scikit-learn pydotplus flask flask-wtf

We'll also need a python library firefly-python that is not available as conda package. Install it using pip.

pip install firefly-python

The notebooks used for the workshop are available in the following git repository. All the participants need to clone this repository before the workshop.

https://github.com/amitkaps/full-stack-data-science

------

##Geospatial data science and analysis using ArcGIS API for Python
####*Rohit Singh*

Rohit Singh is the lead developer of ArcGIS API for Python, at Esri, the world leader in GIS.
 
Rohit graduated from IIT Kharagpur with a degree in Architecture and has extensive experience and passion in the field of software design and development. In a rich career spanning over 18 years, Rohit has worked for large and small companies, including startups as well as global technology behemoths such as IBM and TCS. For the past 15 years, he has worked as a lead software architect and API designer at Esri, the world leader in GIS, and been instrumental in the design and development of several industry leading GIS products such as ArcGIS Engine, ArcGIS Enterprise and the ArcGIS API for Python. He frequently presents at conferences around the world, showcasing the latest developments in the field of geospatial analysis and technology.
 
**Workshop abstract:**
Analysts and data scientists can use the ArcGIS API in combination with data science libraries in Python for mapping, visualization and geospatial data analysis. This live-demo style talk will demonstrate how to perform sophisticated vector and raster analysis, geocoding, map making, routing and directions using a Pythonic API along with Jupyter notebooks and Pandas.
 
**Software Requirements:**
Python 3.5 or 3.6 and Anaconda installed

---------


##Introduction to Julia Programming
####*Sandeep Nagar*

Dr. Sandeep Nagar has done PhD in Material Science and Engineering from The Royal Institute of Technology (KTH), Sweden in 2012. With 13+ years of research experience in nanotechnology and electronics, he is presently working as Faculty in-charge of Electrical and Electronics Engineering Department at G D Goenka University. He has authored 5 books(https://www.amazon.com/author/sandeepnagar) on MATLAB and its open source alternatives like Python, Octave, SCILAB and Julia. His interest includes using embedded system and IoT configurations to design experiments to study interesting Physical phenomenons and simulate them using Python and/or Julia.

**Workshop abstract:** 
Presently workshop will introduce Julia programming language which "Walks like Python and Runs like C" because it is written with simplicity of python but rival execution speed of C language. Workshop will illustrate basic structure of objects, usage of methods, defining loops and functions.

**Software requirements:**
If Uninterrupted internet is available to all (speaker+audience):
User do not need to install any software but can simply make an account at JuliaBox and start working by uploading given Jupyter Notebooks
If user wish to work offline then:
Install Julia from its main website
Open Julia terminal and install package named "IJulia" using command Pkg.add("IJulia")
Run given Jupyter notebook by running the commands:
Using IJulia
notebook()
Notebooks for workshop are under construction and will be shared in some days time.

Also the repository for relevant code files (Jupyter Notebooks) will be https://github.com/yoddha24/IntroJulia.git

-----------

##Create a sense2vec model using Gensim and Spacy from scraped news data and integrate it with Flask
####*Tanu Mittal, Abhishek Kapoor*

*Abhishek Kapoor*
Software engineer who likes to contribute and work with open source and free softwares. Always eager to try new things.

*Tanu Mittal*
An avid coder with a strong interest in projects that require both conceptual and analytical thinking. Fully-committed to develop using Free & Open Source Tools.

**Workshop abstract:** 
This workshop will make users understand how to model multiple embeddings (senses) for a word using NLP techniques. 

**Software Requirements:** 
Python 3, VirtualENV, Git setup

-------------

##Visual Storytelling with D3
####*Alok Kumar Shukla*

After graduating from NIT Allahabad in 2009 with a Bachelors Degree in Information Technology, I have been building intelligent software product suites at enterprise scale. I bring machine learning capabilities to well established product suites in electronic content and business process management verticals. I have also helped build an in-house data analytics framework that enables creation, testing, evaluation and export of  machine learning models in a much more streamlined way than the traditional ad-hoc approach. 
Apart from that, I am a graduate student at first cohort of Data Science masters program offered by University of Illinois Urbana–Champaign in partnership with Coursera. I expect to graduate by Summer 2018. I've taken up classes on Distributed Systems, Methods of Applied Statistics, Text Information Systems, Theory and Practice of Data Cleaning and Data Visualisation. Winter of 2017, I also took Natural Language Processing with Deep Learning class at Stanford as a non-degree student.

If you're passionate about open learning, doing data science the right way; we should connect.

Workshop abstract: If you’re looking for an edge in your resume as a Data Scientist; Data Visualisation is THE skill to add. And, thats not just because it helps in the most crucial part of whole Data Science process - presentation of your results but also because sometimes all you need with your data is a powerful sense of storytelling and a tool to help you achieve just that. Join me in getting your hands dirty with most beautiful library for visual storytelling on the web.

Software Requirements: The attendees should be familiar with basic HTML, CSS and JavaScript. Any Mac/ PC with fairly recent installation of Chrome is required. Choose your favourite code editor - Sublime/ Atom/ Brackets.  Will need internet access to download D3.js . 

---------------------

##Deep Reinforcement Learning: A hands-on approach
####*Shubham Dokania*

Shubham Dokania is current a Researcher at CVIT IIIT-H, supervised by Dr. C.V. Jawahar and Dr. Girish Verma. Previously he was a Machine Learning Instructor at Coding Blocks and Research Intern at IIITD (supervised by Dr. Ganesh Bagler). His current research focus lies in the field of Reinforcement Learning and it's applications. Previously at Coding Blocks, he used to teach undergrad/grad students and industry professionals about the field of Machine Learning while trying to develop a research based thinking. Shubham has spoken at local meetups including PyData Delhi Meetup, DTU, IIITD, IIITH workshop sessions and bootcamps, and has several research articles published at reputed conferences.

**Workshop abstract:**
Deep Reinforcement Learning has been becoming very popular since the dawn of DeepMind's AplhaGo and DQN. Through this workshop, we wish to unravel the underlying workings of these models through simple processes. This workshop aims to provide a simple insight about RL via covering concepts such as MDP, Q-learning, Temporal Difference learning, and finally Deep Q-learning and Deep RL. The workshop will be hands-on with implementation on a few small games including Flappy Bird.

**Software Requirements:**
Ideally, an attendee should have a system with the following:
1. Python2.7 or Python 3
2. Numpy, Matplotlib
3. Theano/Tensorflow
4. Keras
5. PyGame
6. OpenAI gym

It is assumed that the audience has a basic understanding of Machine Learning / Deep Learning, and some familiarity with Neural Networks, CNN etc. (Intermediate level)
It is also recommended (not required) to have a Cuda enabled GPU system if the attendees wish to train the network in the workshop only.


