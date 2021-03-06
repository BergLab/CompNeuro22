# CompNeuro22

☢️ *Please, read carefully all the information here before the course starts*

The course will consists of three types of classes: **Lectures** where you learn some concepts relevant in computational neuroscience, **Coding exercises** where you get to practice what you learn during lecture and **Invited talks** researches will come talk about their current research.

  * The **lectures** will follow a hybrid flipped classroom structure: we will give you some material —typically a video playlist— that you need to watch before coming to class. These materials are meant for you to refresh some notions of build an intuitions about the concepts, during class we will build on them. The links to the supporting material can be found in the course timeline table below.

  * The **coding exercises** will be done in groups, the idea is that you work autonomously on them and ask us if you have questions. 
You're welcome to meet before the exercise class to work through the exercises with your group colleagues or, if you don't have the time to finish them during the session, to finish them afterwards. During the first lecture we will detail the role of the exercises in the exam.
We will have 4 groups named: Drosophila 🪰, C Elegans 🪱, Giant Squid 🦑 and Rattus norvegicus 🐀. We've tried to have balanced groups regarding coding skills. The groups members can seen in Absalon.  

  * The **invited talks**: simply relax and enjoy.  



## 🤓 Before the course starts

### Preparation

If you have never coded or used python before (or it's been a while), we strongly recommend that you take this introduction course to python. It covers all the coding requirements you need for the course: https://www.kaggle.com/learn/python

It's made of 7 lessons covering all you need to know about python to complete our course. Each lesson consist of a **tutorial** and some simple **exercises**. The exercises are hosted online as notebooks so you can do them without installing anything on your computer. 


### Set-up for coding

Similarly to the aforementioned python course, our course exercises will take the form of "notebooks", notebooks a document format that allows you to run code, write text and generate plots in the same document. They are made of *cells*, which can be *code cells* or *text cells*. In most notebooks, you can execute a cell by pressing *Shift + Enter*.

You have two options for doing the exercises: 
  * the simplest one is to use Google Colab which lets you do the exercises online so you don't need to do any set-up on your computer. To open the exercises simply click on badge "Open in Colab" of the notebook and you're ready to start coding. Watch [Introduction to Colab](https://www.youtube.com/watch?v=inN8seMm7UI) for a quick video intro, you'll see that Colab is very similar to the Kaggle notebooks from python intro course. The first week exercices contains a notebook covering the basics of Colab:     <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week1/week1-IntroColab.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' ></a>  

  * The second option is to install an editor (the app where you type code) and python in your computer. This option has the advantage of letting you work more easily with your own data and having some nice extra features. If you pick this option, we recommend you get editor Spyder. A simple way of installing both Spyder editor and Python is to install Anaconda: https://www.anaconda.com/products/distribution . Then you can simply download the notebooks folder in this repository and open them in your computer.

If you're already comfortable using other editor, you're more than welcome to keep it using. 

## 📜 Exercise sessions timeline and weekly supporting material

Here you can find the table of content of each week and its corresponding exercises.


<table class="tg">
  <tr>
    <th class="tg-yw4l"><b>Week</b></th>
    <th class="tg-yw4l"><b>Topic</b></th>
    <th class="tg-yw4l"><b>Description</b></th>
    <th class="tg-yw4l"><b>Notebooks</b></th>
    <th class="tg-yw4l"><b>Supporting material (watch/read before class)</b></th>
  </tr>
  
  <tr>
    <td class="tg-yw4l">1(19)</td>
    <td class="tg-yw4l">Linear algebra and intro python</td>
    <td class="tg-yw4l">Practice basic notions of linear algebra, manipulate numpy arrays, applications of linear systems</td>
    <td class="tg-yw4l">
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week1/week1a-Numpy_Introduction.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >  
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week1/week1b-Linear_Algebra.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >  
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week1/week1c-Applications_LT.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >  
    <td class="tg-yw4l"> 
    - <a href="https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab">Essence of linear algebra</a>  </td>
  </tr>

  <tr>
    <td class="tg-yw4l">2(20)</td>
    <td class="tg-yw4l">Differential equations and neuron models</td>
    <td class="tg-yw4l">Modelling systems and solving differential equations: Predator–prey and LIF neurons</td>
    <td class="tg-yw4l">
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week2/week2a.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >
    <td class="tg-yw4l"> 
    - <a href="https://www.youtube.com/watch?v=p_di4Zn4wz4">Differential equations, a tourist's guide</a>
    <br>
    - <a href="https://youtu.be/ovJcsL7vyrk">Logistic map equation</a>
    </td>
  </tr>

  <tr>
    <td class="tg-yw4l">3(21)</td>
    <td class="tg-yw4l">Simulation of neural population</td>
    <td class="tg-yw4l">Simulate populations of spiking biological neurons with Brian and visualization resulting data</td>
    <td class="tg-yw4l"> 
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week3/week3a.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >  
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week3/week3b.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >  
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week3/week3c.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >  
    <!-- </a><br>
     <a href="https://github.com/BergLab/CompNeuro22/notebooks/week3/" target="_blank"><img align="left" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" height = ''></a></td> -->
    <td class="tg-yw4l">
    - <a href="https://www.youtube.com/playlist?list=PLkBQOLLbi18MCEdPJQ7gdnqP-Z0Tkmcjy">NMA: Biological Neuron Models</a> (skip Q&As)
    </a><br>
    - Chapters from Sterratt: 2.1, 2.2, 7.1, 7.2, 8.2    
    </td>
  </tr>


  <tr>
    <td class="tg-yw4l">4(22)</td>
    <td class="tg-yw4l">Data analysis and Machine learning</td>
    <td class="tg-yw4l">Data analysis w/ Pandas + ML w/ scikit-learn to solve supervised learning problem</td>
    <td class="tg-yw4l">
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week4/week4a.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week4/week4b.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >
    <td class="tg-yw4l">
    - <a href="https://youtube.com/playlist?list=PLZHQObOWTQDNU6R1_67000Dx_ZCJB-3pi">Artificial Neural Networks</a> (videos 1 and 2)
  </tr>

  <tr>
    <td class="tg-yw4l">5(23)</td>
    <td class="tg-yw4l">Network analysis</td>
    <td class="tg-yw4l">Network theory and using NetworkX library to simulate, study and visualize graphs</td>
    <td class="tg-yw4l">
    <a href="https://colab.research.google.com/github/BergLab/CompNeuro22/blob/main/notebooks/week5/week5.ipynb">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >
    <td class="tg-yw4l">N/A
    <!-- <a href="https://www.youtube.com/watch?v=ezL7j4nSXpQ">Complex network analysis with NetworkX
    </a><br>
    Chapters from Sterratt: 2.1, 2.2, 7.1, 7.2, 8.2    
    </td> -->
  </tr>


  <tr>
    <td class="tg-yw4l">6(24)</td>
    <td class="tg-yw4l">Invited talks</td>
    <td class="tg-yw4l">Relax and enjoy</td>
    <td class="tg-yw4l">N/A
    <!-- <a href="https://colab.research.google.com/???????????">
    <img src="https://colab.research.google.com/assets/colab-badge.svg" width = '' >
    </a><br>
     <a href="https://github.com/BergLab/CompNeuro22/notebooks/week3/" target="_blank"><img align="left" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" height = ''></a></td> -->
    <td class="tg-yw4l">N/A
    <!-- <a href="https://www.youtube.com/playlist?list=PLkBQOLLbi18MCEdPJQ7gdnqP-Z0Tkmcjy">NMA: Biological Neuron Models</a> (skip Q&As)
    </a><br>
    Chapters from Sterratt: 2.1, 2.2, 7.1, 7.2, 8.2    
    </td> -->
  </tr>

<!-- https://www.kaggle.com/learn/intro-to-machine-learning -->
<!-- https://scikit-learn.org/stable/tutorial/index.html -->
<!-- https://github.com/AppliedMachineLearningNBI/AppliedML2021 -->
<!-- https://www.nbi.dk/~petersen/Teaching/AppliedMachineLearning2021.html -->

  
 </table> 


## The exam

The exam is an oral exam. You need to prepare an approximately 10 min presentation on each of the topics covered during the course followed by 5 min questions about your presentation, and general questions about the rest of the course content. The specific topic will be randomly picked during the exam. You can choose to use —or not— the week's notebook as support for your presentation (we will provide the notebooks on a projector). After this, the student leaves the room and the censor and examiner find the appropriate grade, which is delivered to the student waiting outside. The grade is a pass/non-pass grade. 


**The five topics for the exam are the following:**

  1. Philosophical aspects of computational neuroscience (Chapter 1.1.1-1.1.5 and introduction lectures). E.g. levels of description. Pros and cons of levels of details in a model. Variables and parameters. (No colab notebook support for this.)


  2. Dynamical systems and differential equations (B.2 - B.2.1 and notebook week 2): In general, terms describe the method of analysis of two coupled dynamical systems, e.g. predator-prey.

  3. One-compartment neuronal models and the integrate-and-fire neuron (sect. 8.2.0 - 8.2.1 and notebooks week 2-3). Explain the different parameters used to run the simulation in the notebook. 

  4. Data analysis and machine learning (Lecture and notebooks week 4): explain linear and nonlinear correlations, how they can be described with correlation coefficients. Supervised machine learning. Difference between regression and classification tasks. Define what an artificial neural network is.

  5. Network science (Lectures, notebook and sect. 9.1.3):  What are a network, random network, and a Small-world network? Why are network useful models for neuroscience? Network measures: mean path length and clustering coefficient. What is the degree of a node and the degree distribution of a network.

## Other resources

An unordered list of resources that you might find useful:

* <a href="https://ipython-books.github.io/">IPython Cookbook: a nice book covering scientific computing with python and notebooks </a>  
* <a href="https://neuronaldynamics.epfl.ch/index.html">Neuronal Dynamics: an online available book covering from neuron models to dynamics cognition.</a>  
* <a href="https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html">Scikit-learn guide to choosing a model </a>  
* <a href="https://cheatsheets.quantecon.org/ ">A summary of how to translate code between Matlab, Python and Julia  </a>  
* <a href="https://www.tomasbeuzen.com/python-programming-for-data-science/README.html ">Python Programming for Data Science  </a>  
* <a href="https://youtu.be/QHj9uVmwA_0">Neural manifolds - The Geometry of Behaviour  </a>  
* <a href="https://brian2.readthedocs.io/en/stable/user/index.html  ">Brian simulator documentation  </a>  
* <a href="https://www.youtube.com/watch?v=oa6rvUJlg7o">An animation of how action potentials work at a cellular level  </a>   
* <a href="https://www.youtube.com/watch?v=YYXdXT2l-Gg&list=PL-osiE80TeTskrapNbzXhwoFUiLCjGgY7">Python for beginners playlist  </a>    
* <a href="https://stats.stackexchange.com/questions/2691/making-sense-of-principal-component-analysis-eigenvectors-eigenvalues">Making sense of principal component analysis, eigenvectors & eigenvalues  </a>    
* <a href="https://missing.csail.mit.edu/0"> The Missing Semester of Your CS Education </a>  
