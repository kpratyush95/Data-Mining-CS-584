Description:
*******************************************************************

This is an individual assignment with maximum size of 1.

********************************************************************

Overview and Assignment Goals:

The objectives of this assignment are the following:
Implement the K-Means Algorithm
Deal with Image data (processed and stored in vector format)
Think about Best Metrics for Evaluating Clustering Solutions

Detailed Description:

* There are 2 leaderboard submissions and this is the main assignment. HW3 - Iris is the other associated assignment with an easier dataset where K-Means can be tested quickly. *

For this assignment, you are required to implement the K-Means algorithm. Please do not use libraries for this assignment except for pre-processing.
Input Data (provided as new_test.txt) consists of 10,000 images of handwritten digits (0-9). The images were scanned and scaled into 28x28 pixels. For every digit, each pixel can be represented as an integer in the range [0, 255] where 0 corresponds to the pixel being completely white, and 255 corresponds to the pixel being completely black. This gives us a 28x28 matrix of integers for each digit. We can then flatten each matrix into a 1x784 vector. No labels are provided.
Format of the input data: Each row is a record (image), which contains 784 comma-delimited integers.
Examples of digit images can be found here
For Evaluation Purposes (Leaderboard Ranking), we will use the V-measure in the sci-kit learn library that is considered an external index metric to evaluate clustering. Essentially your task is to assign each of the instances in the input data to K clusters identified from 1 to K.

For the leaderboard evaluation set K to 10. Submit your best results. The leaderboard will report the V-measure on 50% of sampled dataset.
Some things to note:

The public leaderboard shows results for 50% of randomly chosen test instances only. This is a standard practice in data mining challenge to avoid gaming of the system.
In a 24-hour cycle you are allowed to submit a clustering solution 10 times only. Only one account per student is allowed.
The final ranking will be based on the last submission.
format.txt shows an example file containing 10,000 rows with random class assignments from 1 to 10.

Rules:
This is an individual assignment. Discussion of broad level strategies are allowed but any copying of submission files and source codes will result in honor code violation. Similarly, it's never acceptable to copy code from the internet, even if you cite the source. Doing so will result in honor code violation.
Feel free to use the programming language of your choice for this assignment.
While you can use libraries and templates for dealing with input data you should implement your own K-Means algorithm.
