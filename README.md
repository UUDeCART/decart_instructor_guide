# University of Utah DeCART Summer School for Biomedical Data science
## Instructor Guide

Brian E. Chapman, Ph.D.  
Matthew H. Samore, M.D.  
Donna Zigenfuss, Ed.D.  

## Purpose

The purpose of this repository is to provide guidance in creating instructional materials using [Jupyter notebooks](http://jupyter.org/) to instructors in the DeCART summer school. DeCART is funded in part by the NIH through grant 1R25EB023930-01 "CURRICULUM IN BIOMEDICAL BIG DATA: SKILL DEVELOPMENT AND HANDS-ON TRAINING."

## Objectives of the DeCART Training program


>Advances in genomics and biomedical generate huge amounts of data at the molecular level, while wide spread implementation of electronic medical records has dramatically increased digital documentation of healthcare information The objective of this proposal is to design, develop, and implement a cross-disciplinary, short-term training program in methods for utilizing Big Data in the health and biomedical science domain....Our program will include five knowledge tracks, health sciences, computational methods, data representation, visualization, and statistical analysis. These five tracks will be integrated within interactive learning environment that builds on principles of case-based learning and follows a flipped classroom paradigm. Program participants will be recruited from among trainees in biomedical informatics, molecular biology, population health sciences, and clinical investigation. Our curriculum will enable collaborating scientists to better comprehend the scientific language utilized in other disciplines. This will enhance communication and facilitate development of a synergistic environment which leads to improved overall quality of research studies. Upon completion of our short-term training, participants will be equipped to bootstrap their own big data research projects, participate in teams tackling big data problems in biomedicine, and pursue additional training in biomedical data sciences. The University of Utah is an ideal place for conducting this training with its superb collaborative academic environment. The University is home to the oldest academic biomedical informatics department in the country, Intermountain Healthcare is recognized as one of the world leaders in integrating informatics into clinical care, and the Salt Lake VA, is the center of VA’s major informatics initiatives. Researchers from these three sites are being brought together to train the next generation of big data professionals equipped to propel data-driven analytics in medicine.

## Principles

DeCART is intended to to provide both an in-person [summer school](https://datascience4health.bmi.utah.edu/) and a self-directed on-line learning environment. As such, we want to leverage our in-person summer school to help guide the development of the self-directed learning experience. Therefore, we would like the instructors to work primarily with the environment we will use for the self-directed environment. We acknowledge that this imposes constraints that you may not be used to in a traditional classroom.

1. Materials are open.
  1. Use of YouTube
      1. YouTube videos can be embedded into the Jupyter notebooks.
      1. The BD2K education coordination center wants to index all our YouTube videos.
  1. Use of open data
    1. Eliminates the need for managing DUA and verifying appropriate training (e.g. CITI)
    1. Maximize the number of people that can train and thus our impact.
1. Use of Python
>For our curriculum we will use Python as our primary programming language. Python is the most popular introductory programming language at top computer science and electrical engineering departments in the United States. (Philip Guo, [“Python is Now the Most Popular Introductory Teaching Language at Top U.S. Universities”](https://cacm.acm.org/blogs/blog-cacm/176450-python-is-now-the-most-popular-introductory-teaching-language-at-top-u-s-universities/fulltext))
>
>The adoption of Python as a first programming language is likely driven both by market forces and pedagogical benefits. There has been a nearly 600% increase in Python job positions since 2006. (“Is Python Becoming the King of the Data Science Forest?”) According to the January 2015 Red Monk survey of program language activity, Python is the 4th most active language (behind JavaScript, Java, and PHP), as measured by GitHub and Stack Overflow activity. (“The RedMonk Programming Language Rankings: January 2015”) Other relevant language rankings include Ruby (tied for 5th with C#, and C++), R (13), Matlab (16).
>
>Pedagogical benefits of Python are related to its syntactic simplicity. In a longitudinal (four year) study of a large cohort (761) of students, Koulouri et al.3 found that students had a stronger grasp of fundamental programming concepts when taught with a syntactically simple language (Python) than when they were taught with a more complex language (Java). Stefik et al. studies how easily novice students learned the syntax of six programming languages compared to a randomly generated programming syntax. They found that novices were no better at learning the syntax of complex languages such as Java or Perl than they were able to understand the random syntax. However, they learned markedly better with Python and Ruby, languages known for their simple syntax4. Denny et al. found a negative correlation between the frequency of syntax errors by students and their attitude about programming5. In short, students learning a more complex language are more likely to make more frequent, more difficult to correct syntax errors and are thus more likely to be frustrated with and lose interest in programming.
>
>Not only is Python an excellent learning language it is a very respectable and popular language for a variety of applications found in a variety of settings. The early philosophy at Google of "Python when we can, C++ when we have to,"" is a good summary of how Python is often used. Its ease and flexibility make for very rapid development, although its weaknesses (e.g. execution speed) sometimes require stepping to another language when an application is deployed.
>
>Python's position in data science has been particularly robust. In biomedical sciences, must of the challenge in data science relates to structuring data from unstructured sources such as images and free text. Scikit-image and SimpleITK for image analysis, NLTK, TextBlob, and Gensim for language processing. Recent big data tools such as Spark natively provide a Python interface, and while its analytic toolset is not as mature as R, recent package developments make Python suitable for most analytic problems.

1. Use of JupyterHub. We taught the summer school with our Jupyterhub instance last summer as well as a full semester introductory programming course last fall. Use of the Jupyterhub environment greatly facilitated the students getting up to speed with learning without struggling with software installation, data downloads, etc. to their own computer.

## Working with Jupyter notebooks

Jupyter notebooks are a generalization of IPython notebooks (renamed because multiple languages are now supported). [Here is a Nature article about IPython notebooks](http://www.nature.com/news/interactive-notebooks-sharing-the-code-1.16261)

* [Official Jupyter gallery of interesting notebooks](https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks)
* [Teaching with IPython:Jupyter Notebooks and JupyterHub](https://bids.berkeley.edu/resources/videos/teaching-ipythonjupyter-notebooks-and-jupyterhub)
* [Using Jupyter Notebooks to teach computational literacy](http://www.elearning.eps.manchester.ac.uk/blog/2016/using-jupyter-notebooks-to-teach-computational-literacy/)


## Pedagogy

## Teaching On-line

In funding this project, the NIH was most interested in our plan to create an on-line, self-directed learning environment. While we are big believers in in-person instruction, we simply cannot reach/train the number of students the NIH is interested in our face-to-face courses. We hope to leverage our yearly summer school to enhance the on-line environment we create. Leveraing the Jupyterhub environment facilates both our in-person and on-line aims.

&copy; 2017 Brian Chapman, Matt Samore, Donna Zigenfuss
