

## Introduction

The lab course serves as a supplement to the theoretical part of machine learning course, with the following objectives:

1. By implementation, reviewing concepts from the theoretical content covered in the lectures.
2. Develop intuition about how algorithmic designs affect testing performance.
3. Gaining a basic familiarity with commonly used Python packages such as sklearn, numpy, and pytorch.

### Course format and platform

The students do coding. We will use [[google colab]](https://colab.research.google.com/) as a platform for exercises.  
                
## Instructors

- Instructor: Dr. Yangchen Pan (Email: yangchen.eng.ox@gmail.com)
- TAs: Aleix Segui Ugalde, Aniq Rahman, Angel He, Kevin Qinghong Lin, Yishun Lu.

## Lab Policy

## Attendance

In the afternoon, the instructor will ask each student to sign the attendance sheet. If you finish the required exercises before signing, please see the instructor to have your attendance recorded. You may leave only after you have signed the attendance sheet and submitted your completed exercises.

Please go to the registered session unless officially justified evidence is provided. Any absence should be reported to the student office and cc the instructor. 

## Submission

1. Please email the **links** of your completed Google Colab files (either multiple files or a single combined file is fine) to the instructor at **yangchen.eng.ox@gmail.com** no later than 5 p.m. (the end of your session), using the subject line:

   **YourName-SessionDate[DD/MM]-mllab2026**
   
2. Only submissions received by 5:00 p.m. will be considered for grading. I understand that some of you may have special requests. Please feel free to contact the instructor; additional time may be granted without penalty. 

3. You may skip up to 6 questions without penalty. There are 17 questions in total. Therefore, you must submit at least 11 questions. You may submit more than 11, but only the first 11 will be graded.

4. Remember to set the visibility of your Google Colab file to “Anyone with the link.” Click Share, then under “General access,” change the setting to “Anyone with the link.” 

### Collaboration

#### AI-based coding tools, such as ChatGPT, Copilot, and similar, are strictly forbidden in this lab. To turn it off, once you open a Colab file, go to Tools > Settings > AI Assistance > Hide Generative AI Features, and deselect the other options. Discussion is encouraged, and the correct answer should come from your own effort. 

### Time/Break

Lab runs from 11:00 am - 5:00 pm, Software Lab B.

Lunch break: 12:45 pm - 2:15 pm

## Content

We will use [[google colab]](https://colab.research.google.com/) as a platform for exercises. 

**NOTE: the exercises are not good to use before your session officially starts, as there might be last-minute updates.**

**Suggestions on how to approach the exercises:** 

1. Avoid spending too much time on a single question. Aim to complete as many questions as you can initially, and then return to the ones you found challenging.
2. The exercises are designed to be (mostly) self-contained, serving as a tutorial. For example, you should be able to learn how to define/train a simple neural network in PyTorch by examining the provided code. Feel free to consult the official documentation for some functions if necessary.
3. We encourage you to try solving problems on your own first, but we are always here to help if you need it. 
4. Reviewing the relevant lecture slides could be helpful.
5. **For each colab file below, you should MAKE A COPY in your own google drive to edit & run. And remember to save your answer!!!!!!!!!**

### short intro (you may simply skip this section if you are already familiar with these tools)

- [[env intro]](https://colab.research.google.com/drive/1DHVIdXVouXhQmnusmR-JLGBqT2_TsxCF?usp=sharing): Colab/Markdown/latex intro

- [[Numpy]](https://colab.research.google.com/drive/1N_LQdkRL-PrQqtrUtKOXDDRxKW7Whioh?usp=sharing): Good enough to know matrix-matrix/vector products

- [[Object Oriented Programming]](https://colab.research.google.com/drive/1rWW_xM-Yv9tIyNGRF5QtWpjaCz0KajLu?usp=sharing): May be helpful to read first few paragraphs

- Pytorch (see exercise)

### Part I: Supervised learning

- [[Regression]](https://colab.research.google.com/drive/1ZdImDbejqFlphpuEfo-DDWUYtumuEXZt?usp=sharing) [**Regression: 4 Questions**]

- [[SVM Classification]](https://colab.research.google.com/drive/1KoBV0mC0MZ8gvHeH5OsBaUZF9jtYbVWd?usp=sharing) [**Classification: 2 Questions**]

### Part II: Unsupervised learning 

- [[Laplace Approximation]](https://colab.research.google.com/drive/1vd-B0jSvckiCQBtG_f7O9mQ7kcghM_sA?usp=sharing)  [**Laplace Approximation: 2 Questions**]

  A potential point of confusion: Laplace Approximation is a Bayesian inference technique that can be applied in both supervised and unsupervised learning problems. While it is categorized under unsupervised learning in this exercise, keep in mind that its applications extend beyond this context.

- [[Sampling Approaches]](https://colab.research.google.com/drive/1LhYEb2MFJtu5qs9BtselyCgkVaRYo1Nm?usp=sharing): [**Inverse transform, rejection, metropolis: 4 Questions**]

- [[(Variational) Autoencoders]](https://colab.research.google.com/drive/1trrFLB4HGk8Q4q14SnfJAk63fkAJDRiI?usp=sharing) [**Autoencoder: 5 Questions**]
