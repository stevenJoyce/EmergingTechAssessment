# EmergingTechAssessment
In this repository you will find one ipynb file. This file is called Tasks.ipynb <br/>
This is the only runnable file in the repository. <br/>
It it written in Python3. <br/>
The file Tasks.ipynb contains the completed Tasks. <br/>
The tasks set out for this assignment <br/>
Task 1 <br/>
Write a Python function called sqrt2 that calculates and prints to the screen the square root of 2 to 100 decimal places. <br />
Your code shouldnot depend on any module from the standard library1 or otherwise. <br/>
You should research the task first and include references and a description of your algorithm. <br/>
Task 2 <br/>
The Chi-squared test for independence is a statistical hypothesis test like a t-test. <br/>
It is used to analyse whether two categorical variables are independent. <br/>
The Wikipedia article gives the table below as an example [4], stating the Chi-squared value based on it is approximately 24.6.<br/>
Use scipy.stats to verify this value and calculate the associated p value. <br/>
You should include a short note with references justifying your analysis in a markdown cell. <br/>
Task 3 <br/>
The standard deviation of an array of numbers x is calculated using numpy as np.sqrt(np.sum((x - np.mean(x))** 2)/len(x)) .<br/>
However, Microsoft Excel has two different versions of the standard deviation calculation, STDEV.P and STDEV.S . <br/>
The STDEV.P function performs the above calculation but in the STDEV.S calculation the division is by len(x)-1 ratherthan len(x) . <br/> Research these Excel functions, writing a note in a Markdown cell about the difference between them. <br/>
Then use numpy to perform a simulation demonstrating that the STDEV.S calculation is a better estimate <br/>
for the standard deviation of a population when performed on a sample. <br/>
Note that part of this taskis to figure out the terminology in the previous sentence. <br />
Task 4 <br/>
NB – when I first posted this task, I accidentally
wrote “k-means” where I meant to write “kNN” for k Nearest Neighbours. Because of this, I will allow either algorithm to be used and have
extended the deadline by two weeks. Use scikit-learn to apply k-means clustering to Fisher’s famous Iris data set. You will easily obtain a copy of the data set online. Explain in a Markdown cell how your code works and how accurate it might be, and then explain how your model could be used to make predictions of species of iris. <br/>
<br/>
