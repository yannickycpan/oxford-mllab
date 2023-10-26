

## Introduction

The course serves as a supplement to the machine learning class taught in MT 2023, with the following objectives:

1. Deepen and explore the understanding of theoretical knowledge.
2. Develop intuition about how algorithmic designs impact testing performance.
3. Enhance coding skills.
4. Gain experience in using new technologies to solve real-world problems and learn about unfamiliar concepts.

### Course format and platform

We will start with a short lecture and then the students do coding. We will use [[google colab]](https://colab.research.google.com/) as a platform for exercises.  
                
## Instructors

- Instructor: Dr. Yangchen Pan (Email: yangchen.eng.ox@gmail.com)
- TAs: TBD

## Course Policy

### Policy on ChatGPT

Students can ask ChatGPT to provide code assistance only for option 3. For options 1 and 2, students can request non-coding assistance from ChatGPT.

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

- Q1. Regression: I will provide a simple dataset and learning curves resulting from various algorithmic designs (e.g., with/without regularization, different optimizers like SGD/Adam, and different hyperparameter settings). Students should:

  1. Predict which algorithmic design corresponds to a given learning curve.
  2. Implement the algorithms with corresponding algorithmic choices to reproduce the learning curves. Some mathematical derivations may be required before coding.
  3. Estimate training sample density function and draw samples from it.  (TBD)

Algorithms covered: L2 regularization, Naive Bayes, using different function approximators (linear and neural networks).

- Q2. Classification: SVM and logistic regression and logistic with NNs. Students should:
  1. Visualize decision boundaries and explain the differences between algorithms.
  2. Investigate how different hyperparameter choices and data separability impact the decision boundary.
  3. Estimate training sample density function and draw samples from it.  (TBD)

### Option 2: Semi/Unsupervised learning

- Q1. Generative Models. Autoencoders: Students will implement various autoencoders, including sparse, denoising, and conditional types. I will provide task descriptions, and students will select the appropriate method or combination of methods for the task and draw samples from the autoencoders. 

- Q2. Comparative Analysis of Latent SVM and Another Algorithm in Object Detection: Students will:
  1. Predict which algorithm performs better for specific object detection tasks.
  2. Implement the chosen algorithms to validate their predictions.

### Option 3: ChatGPT-assisted Coding

- Q1. Uncommon Algorithm Implementation: An algorithm that's not taught in the MT2023, possibly a matrix factorization algorithm or a gamma regression, will be presented in a non-Python programming language not covered in the class. Students needs to implement in Python to achieve the desired performance, with the help of ChatGPT.

- Q2. Time-Restricted Task: Students must complete this question within a set time limit, which I will monitor in class. A dataset is provided, and students will utilize ChatGPT to complete the entire pipeline, from data preprocessing to achieving a target testing performance using a machine learning algorithm.
