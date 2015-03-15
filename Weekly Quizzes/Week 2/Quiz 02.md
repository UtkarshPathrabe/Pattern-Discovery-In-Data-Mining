Quiz 02
=======  

Question 01
-----------  
Suppose a school collected some data on students' preference for hot dogs(HD) vs. hamburgers(HM). We have the following 2×2 contingency table summarizing the statistics. If lift is used to measure the correlation between HD and HM, what is the value for lift(HD, HM)?  
![Fig 1](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig01.png "Fig 1")  

#### Answer  
1  

![Fig 2](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig02.png "Fig 2")  

Question 02
-----------  
Suppose Coursera collected statistics on the number of students who take courses on data mining (DM) and machine learning (ML). We have the following 2×2 contingency table summarizing the statistics. If χ2 is used to measure the correlation between DM and ML, what is the χ2 score?  
![Fig 3](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig03.png "Fig 3")  

#### Answer  
562.5  

![Fig 4](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig04.png "Fig 4")  

Question 03
-----------  
What is the value range of the Lift measure?  

#### Answer  
![Fig 5](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig06.png "Fig 5")  

![Fig 6](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig05.png "Fig 6")  

Question 04
-----------  
Which of the following measures is NOT null invariant?  

#### Answer  
![Fig 7](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig07.png "Fig 7")  

![Fig 8](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig08.png "Fig 8")  

Question 05
-----------  
Suppose we are interested in analyzing the transaction history of several supermarkets with respect to purchase of apples(A) and bananas(B). We have the following table summarizing the transactions.  
![Fig 9](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig09.png "Fig 9")  
Denote li as the lift measure and ki as the Kulcyzynski measure for supermarket Si(i = 1, 2). Which of the following is correct?  

#### Answer  
l1 ≠ l2, k1 = k2  

![Fig 10](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig10.png "Fig 10")  

Question 06
-----------  
A store had 100,000 total transactions in Q4 2014. 10,000 transactions contained eggs, while 5,000 contained bacon. 2000 transactions contained both eggs and bacon. Which of the following choices for the value of ε is the smallest such that {eggs, bacon} is considered a negative pattern under the null-invariant definition?  

#### Answer  
0.5  

![Fig 11](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig11.png "Fig 11")  

Question 07
-----------  
![Fig 12](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig12.png "Fig 12")  
Given the itemsets in Table 1, which of the following patterns are in the δ-cluster containing the pattern {A, C, E, S} for δ = 0.0001?  

#### Answer  
{F, A, C, E, S}  

![Fig 13](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig13.png "Fig 13")  

Question 08
-----------  
![Fig 14](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig14.png "Fig 14")  
Given the transactions in Table 2, which of the following is a (1, 0.5)-robust pattern in the database? Select all that apply.  

#### Answer  
None of the other options are correct.  

![Fig 15](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig15.png "Fig 15")  

Question 09
-----------  
A constraint is anti-monotone if an itemset S violates the constraint, so do all of its supersets. Which of following constraints is anti-monotone?  

#### Answer  
range(S.price) < 10  

![Fig 16](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig16.png "Fig 16")  

Question 10
-----------  
A constraint is monotone if an itemset S satisfies the constraint, so do all of its supersets. Which of following constraints is monotone?  

#### Answer  
min(S.price) < 15  

![Fig 17](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig17.png "Fig 17")  

Question 11
-----------  
A constraint is succinct if the constraint c can be enforced by directly manipulating the data. Which of following constraints is succinct  

#### Answer  
max(S.price) > 20  

#### Explanation  
Start with only items whose price > 20 and remove transactions with low-price items only (pattern + data space pruning).  
![Fig 18](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/Weekly%20Quizzes/Week%202/Fig18.png "Fig 18")  
