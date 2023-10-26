

## Introduction

The course is a supplementary component to the machine learning class taught in MT 2023. The objectives are:
1. Deepen and examine the understanding of learned theoretical knowledge 
2. Develop intuition regarding how algorithmic designs affect testing performance
3. Enhance coding skills
4. Get a taste of using new tech to learn unknown things to solve real world problems


### Course format and platform

We will start with a short lecture and then the students do coding. We will use [[google colab]](https://colab.research.google.com/) as a platform for exercises.  
                
## Instructors

- Instructor: Dr. Yangchen Pan (Email: yangchen.eng.ox@gmail.com)
- TAs: TBD

## Course Policy

### Policy on ChatGPT

Students can ask GPT to provide code assistance only for option 3. For options 1 and 2, students can request non-coding assistance from ChatGPT.

### Grading and Attendance

Before leaving, please ask the instructor or TAs to review your completed exercises. After that, please sign the attendance sheet.

**Assignments can be completed in group with at most 3 people, and discussion is encouraged. Everyone in a group receives the same grade.**

Students should go to the assigned session unless officially justified evidence is provided (e.g., doctor's note). 

### Break

Lunch break: 11:50 am - 1:20 pm

## Schedule

You are provided three options below and required to complete 1.5 option (one option + one question from another option). We will use [[google colab]](https://colab.research.google.com/) as a platform for exercises. 

**NOTE 1: for each colab file below, you should make a copy in your own google drive to edit & run.**

**NOTE 2: the content is not good to use before the class officially starts, as there might be last-minute updates.**

### short lecture (<= 0.5 hour)

- Course Introduction

- Colab/Markdown/latex intro [[env intro]](https://colab.research.google.com/drive/1DHVIdXVouXhQmnusmR-JLGBqT2_TsxCF?usp=sharing) 

- Python Basics 
[[Numpy]](https://colab.research.google.com/drive/1N_LQdkRL-PrQqtrUtKOXDDRxKW7Whioh?usp=sharing)
[[Strings]](https://colab.research.google.com/drive/16QB0e6reXr0aYg3QMJbb2Kjpd93cZ1qJ?usp=sharing)
[[Lists]](https://colab.research.google.com/drive/1cHDaCeHUbNzV-zHpYPRBMNohL4dbxeqB?usp=sharing)
[[Dictionaries]](https://colab.research.google.com/drive/1pofof5pxzbliUlgZOKAA5LdA6YMqGGuK?usp=sharing)
[[Tuples]](https://colab.research.google.com/drive/1nqqTPS9GZYyQ9rdCPbMZFWoKdmjtFZv9?usp=sharing)

- Pytorch Tutorial [[Tutorial]]()

### Option 1: Supervised learning

- Q1. Regression. I will provide a dataset and several testing performances in the form of learning curves resulting from several algorithmic designs (e.g. w/wo regularization, different optimizers (SGD/Adam), and hyperparameter settings (regularization weight, learning rate). Students need to: 1) guess which algorithmic design results in a certain learning curve; and 2) do coding to verify their guesses (reproduce those learning curves). Some math derivations may be needed before coding. 

Algorithms to be covered: l2, Naive Bayes, with different function approximators (linear and NNs). 

- Q2. Classification. SVM and logistic regression. The students need to 1) visualize decision boundary and explain why different algorithms result in different boundary; 2) investigate how different hyper-parameter choices and data separability would affect the decision boundary.

### Option 2: Semi/Unsupervised learning

- Q1. Generative models: autoencoder. They will need to implement several commonly seen autoencoders: sparse, denoising, and conditional. I will provide a task description and they choose the right method or combination of methods to use. 

- Q2. Compare latent SVM and another algorithm on two types of object detection task. The students are required to 1) guess which algorithm perform better on a certain task; 2) do coding to verify their guess. 

### Option 3: ChatGPT-assisted Coding

- Q1. An uncommonly seen algorithm (I likely give a matrix factorization algorithm  or a gamma regression) is given in a non-python programming language (that are unlikely covered in the class), the students are allowed to query GPT to implement the algorithm in python to get desired performance.  

- Q2. Time-restricted task: the students must finish this question within a time budget and I will do the timing in class. A dataset is provided. The student needs to use ChatGPT to finish a whole pipeline of applying a ML algorithm, from data preprocessing to achieving a target testing performance. 
