CS583: Deep Learning
============


> Instructor: Shusen Wang

> TA: Xuting Tang and Sesha Vadlamudi


Description
---------

**Meeting Time:**

- Section A: Thursday, 6:30-9:00 PM, Online

- Section B: Friday, 3:00-5:30 PM, Online


**Office Hours:**

- Thursday, 9:00-10:00 PM, virtual

- Friday, 5:30-6:30 PM, virtual



**Contact the Instructor:**

- For questions regarding grading, talk to the instructor during office hours or send him emails.

- For technical questions, post the question on the "discussion" module of Canvas or ask the instructor during the office hours.


**Prerequisite:**

- Elementary linear algebra, e.g., matrix multiplication, eigenvalue decomposition, and matrix norms.

- Elementary calculus, e.g., convex function, differentiation of scalar functions, first derivative, and second derivative.

- Python programming (especially the Numpy library) and Jupyter Notebook.


**Goal:** 
This is a practical course; the students will be able to use DL methods for solving real-world ML, CV, and NLP problems. The students will also learn math and theories for understanding ML and DL.


<span style="color:red">**Slides:** All the slides are available here:</span> [[link](https://github.com/wangshusen/DeepLearning)]


Schedule
---------


- Preparations

	* Install the software packages by following [[this](https://github.com/wangshusen/CS583-2019F/blob/master/homework/Prepare/HM.pdf)].
	
	* Study elementary matrix algebra by following [[this book](http://vmls-book.stanford.edu/vmls.pdf)].
	
	* If you are unfamilar with matrix computation, you need to watch the recorded lectures of CS600:
	
	    - Addition and multiplication [[slides](https://github.com/wangshusen/AdvancedAlgorithms/blob/master/Slides/5_Matrix_1.pdf)]
	  [[video](https://youtu.be/ZTtW6SMTmcY)].
	
	    - Dense and sparse matrix data structures [[slides](https://github.com/wangshusen/AdvancedAlgorithms/blob/master/Slides/5_Matrix_2.pdf)]
	  [[video](https://youtu.be/fy_dSZb-Xx8)].
	
	* Study probability theory and randomized algorithms by watching the recorded lectures of CS600:
	
	    - Monte Carlo [[slides](https://github.com/wangshusen/AdvancedAlgorithms)]
	  [[video](https://youtu.be/CmpWM2HMhxw)].
	
	    - Random permutation [[slides](https://github.com/wangshusen/AdvancedAlgorithms)]
	  [[video](https://youtu.be/xaSBvljOQkc)].
	
	* Finish the [[sample questions](https://github.com/wangshusen/CS583-2019F/blob/master/homework/Quiz1-Sample/Q1.pdf)] before Quiz 1.


- Feb 4/5, Lecture 1

    * ML Basics
    
    * Linear Regression
    
    
- Feb 11/12, Lecture 2

    * Read these in advance: 
    [[Matrix Calculus](https://github.com/wangshusen/CS583A-2019Spring/blob/master/reading/MatrixCalculus.pdf)]
    [[Logistic Regression](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Logistic/paper/logistic.pdf)]

    
    * Polynomial Regression
    
    * Classification: logistic regression.
    
    
    
    
- Feb 18/19, Lecture 3
    
    * Classification: SVM.

    * Regularizations.


- Feb 21, 8:30PM - 10:00PM, **Quiz 1**, online

	* Coverage: vectors norms ($\ell_2$-norm, $\ell_1$-norm, $\ell_p$-norm, $\ell_\infty$-norm), vector inner product, matrix multiplication, matrix trace, matrix Frobenius norm, scalar function differential, convex function, use Numpy for matrix computation, randomized algorithm, and ML basics.
	
	* Time limit: 60 minutes
  


- Feb 25/26, Lecture 4

    * Classification: SVM, softmax classifier, and KNN.
    
    * Scientific computing.


- Mar 4/5, Lecture 5

    * Read Sections 1 to 4 in advance: [[neural networks and backpropagation](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/BP/bp.pdf)]
            
    * Neural networks.
    
    * Keras.


- Mar 11/12, Lecture 6
    
    * Convolutional neural networks (CNNs).
    
    * CNNs: Useful tricks
        

- Mar 18/19, Lecture 7

    * Read the note in advance: [[lecture note](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Parallel/Parallel.pdf)] 
    
    * CNNs: batch normalization, theories.



    
- Mar 25/26, Lecture 8
    
    * CNN architectures.
    
    * Parallel computing.    


- Mar 28, 8:30PM - 10:00PM, **Quiz 2**, online

	* Coverage: vector and matrix operations, gradients, ML basics, neural networks, CNNs, parallel computing.
	
	* Time limit: 30 minutes. 

	* Sample: [[click here](https://github.com/wangshusen/CS583-2020S/blob/master/homework/Exam-Sample/Sample.pdf)]
	

- Apr 1/2, Lecture 9

    * Federated learning.

    * Text processing.
    
    * Simple RNN.

    

    
    
- Apr 8/9, Lecture 10

    * RNNs: LSTM, Text generation, machine translation.
	
    
- Apr 15/16, Lecture 11

    * Attention and self-attention.

    * Transformer and BERT.


    
- Apr 22/23, Lecture 12

    * Autoencoders.
    
    * Variational Autoencoder (VAE).
    
    * Adversarial Robustness.


- Apr 25, 8:30PM - 10:00PM, **Quiz 3**, online

	* Coverage: ML basics, CNNs, RNNs, and Transformer.
	
	* Time limit: 50 minutes. 


- Apr 29, 7:00AM - 6:00PM, **Bonus Quiz**, online

	* Coverage: Deep Reinforcement Learning.
	
	* Time limit: 30 minutes. 
	
    
- Apr 29/30, Lecture 13

    * GAN.
    
    * Deep Reinforcement Learning.
    
    
- May 6/7, Lecture 14

    * Deep Reinforcement Learning (Cont.)
    
    
- May 16, 8:30PM - 10:30PM, **Bonus Quiz**, online

	* Coverage: Everything, Including Monte Carlo, Transformer, BERT, Few-Shot Learning, Deep Reinforcement Learning.
	
	* Time limit: 100 minutes. 





Assignments and Bonus Scores
---------

- Homework 1: Linear Algebra Basics

	* Available only on Canvas (auto-graded.)
	
	* Submit to Canvas before Feb 21.
	
 
- Homework 2: Implement Numerical Optimization Algorithms

	* Available at the course's repo [[click here](https://github.com/wangshusen/CS583-2021S/tree/master/homework)].
	* You will need the knowledge in the lecture note: [[Logistic Regression](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Logistic/paper/logistic.pdf)]
	
	* Submit to Canvas before Mar 7.

 	
- Homework 3: Machine Learning Basics

	* Available only on Canvas (auto-graded.)

	* Submit to Canvas before Mar 21.
	
 
- Homework 4: Implement a Convolutional Neural Network

	* Available at the course's repo [[click here](https://github.com/wangshusen/CS583-2021S/tree/master/homework)].
	
	* Submit to Canvas before Mar 28.
	
 
- Homework 5: Implement a Recurrent Neural Network

	* Available at the course's repo [[click here](https://github.com/wangshusen/CS583-2021S/tree/master/homework)].
	
	* Submit to Canvas before Apr 25.
	
	* You may get up to 2 bonus scores by doing extra work. 
	
	
- Bonus 1: Implement Parallel Algorithms (Voluntary)

	* Available at the course's repo [[click here](https://github.com/wangshusen/CS583-2021S/tree/master/homework)].
	
	* You will need the knowledge in the lecture note: [[Parallel Computing](https://github.com/wangshusen/DeepLearning/blob/master/LectureNotes/Parallel/Parallel.pdf)]
	
	* You can choose to implement Federated Averaging or/and Decentralized Optimization. You may get up to 2 bonus points for each. 
	
	* Submit to Canvas before Apr 11 (firm deadline).

 
- Bonus 2: Implement an Autoencoder Network (Voluntary)

	* Available at the course's repo [[click here](https://github.com/wangshusen/CS583-2021S/tree/master/homework)].
	
	* You may get up to 1 bonus point. 
	
	* Submit to Canvas before May 1 (firm deadline).	
	


Textbooks
---------

**Required** (Please notice the difference between "required" and "recommended"):

- Francois Chollet. Deep learning with Python. Manning Publications Co., 2017. (Available online.)

**Highly Recommended**:

- S. Boyd and L. Vandenberghe. Introduction to Applied Linear Algebra. Cambridge University Press, 2018. (Available online.)

**Recommended**:

- Y. Nesterov. Introductory Lectures on Convex Optimization Book. Springer, 2013. (Available online.)

- D. S. Watkins. Fundamentals of Matrix Computations. John Wiley & Sons, 2004.

- I. Goodfellow, Y. Bengio, A. Courville, Y. Bengio. Deep learning. MIT press, 2016. (Available online.)
    
- M. Mohri, A. Rostamizadeh, and A. Talwalkar. Foundations of machine learning. MIT press, 2012.
    
- J. Friedman, T. Hastie, and R. Tibshirani. The elements of statistical learning. Springer series in statistics, 2001. (Available online.)



Grading Policy
---------
**Grades**:

- **A**: 93 and above.

- **A-**: [90, 93)

- **B+**: [87, 90)

- **B**: [83, 87)

- **B-**: [80, 83)

- **C+**: [77, 80)

- **C**: [73, 77)

- **Fail**: below 73


**Weights**:

- Homework 50\%

- Quizzes 30\%

- Final 20\%

- Bonus


**Expected grade on record**:

- An average student is expected to lose at least 10 points. 

- If an average student does not collect any bonus score, his grade on record is expected to be "B+".
An average student needs at least 3 bonus scores to get "A".

- According to Stevens's policy, a score lower than 73.0 will be fail.


**Late penalty**:

- Late submissions of assignments or project document for whatever reason will be punished. 2\% of the score of an assignment/project will be deducted per day. For example, if an assignment is submitted 15 days and 1 minute later than the deadline (counted as 16 days) and it gets a grade of 95\%, then the score after the deduction will be: 95\% - 2*16\% = 63\%.

- All the deadlines for bonus are firm. Late submission will not receive bonus score.

- May 1 is the firm deadline for all the homework and the course project. Submissions later than the firm deadline will not be graded.


