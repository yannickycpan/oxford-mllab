

## Introduction

The lab course serves as a supplement to the theoretical part of machine learning course, with the following objectives:

1. By implementation, reviewing concepts from the theoretical content covered in the lectures.
2. Develop intuition about how algorithmic designs affect testing performance.
3. Gaining a basic familiarity with commonly used Python packages such as sklearn, numpy, and pytorch.

### Course format and platform

The students do coding. We will use [[google colab]](https://colab.research.google.com/) as a platform for exercises.  
                
## Instructors

- Instructor: Dr. Yangchen Pan (Email: yangchen.eng.ox@gmail.com)
- TAs: Aniq Rahman, Angel He, Kevin Qinghong Lin, Yishun Lu.

## Course Policy

### Grading and Attendance

1. In the afternoon, the instructor will go to each of you for you to sign the attendance sheet. If you complete the required exercises before signing, please feel free to see the instructor to have your attendance recorded. Please email the **links** of your completed Google Colab files (either multiple files or a single combined file is fine) to the instructor at yangchen.eng.ox@gmail.com no later than 5 p.m. (the end of your session), using the subject line: YourName-SessionDate-mllab2026. After you have signed the attendance sheet **and** submitted your completed exercises, you are free to leave.  

2. If you cannot complete it before the end of your session, please contact the instructor; you may be given additional time to submit without penalty. 

3. Discussion is encouraged, and the correct answer should come from your own effort.

4. Please go to the registered session unless officially justified evidence is provided (e.g., doctor's note). Any absence should be reported to the student office. 

5. You are allowed to skip at most 6 questions without penalty. There are 17 in total.  

### AI-based coding tools, such as ChatGPT, Copilot, and similar, are strictly forbidden in this lab. To turn it off, once you open a Colab file, go to Tools > Settings > AI Assistance > Hide Generative AI Features, and deselect the other options.

### Time/Break

Lab runs from 11:00 am - 5:00 pm, Software Lab B.

Lunch break: 12:45 pm - 2:00 pm

## Content

We will use [[google colab]](https://colab.research.google.com/) as a platform for exercises. Sufficient hint/code will be provided in the colab file. 

**NOTE: the exercises are not good to use before your session officially starts, as there might be last-minute updates.**

**Suggestions on how to approach the exercises:** 

1. Avoid spending too much time on a single question. Aim to complete as many questions as you can initially, and then return to the ones you found challenging.
2. The exercises are designed to be (mostly) self-contained, serving as a tutorial. For example, you should be able to learn how to define/train a simple neural network in PyTorch by examining the provided code. Feel free to consult the official documentation for some functions if necessary.
3. We encourage you to try solving problems on your own first, but we are always here to help if you need it. 
4. Reviewing the relevant lecture slides could be helpful.
5. **For each colab file below, you should make a copy in your own google drive to edit & run. Again, remember to disable the AI tools.**

### short intro (you may simply skip this section if you are already familiar with these tools)

- [[env intro]](https://colab.research.google.com/drive/1DHVIdXVouXhQmnusmR-JLGBqT2_TsxCF?usp=sharing): Colab/Markdown/latex intro

- [[Numpy]](https://colab.research.google.com/drive/1N_LQdkRL-PrQqtrUtKOXDDRxKW7Whioh?usp=sharing): Good enough to know matrix-matrix products

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
