Quiz 01
=======  

Question 01
-----------  
Which of the following tasks does not fall under the scope of data mining? Select all that apply.  

### Answer  
* Data Cleaning.  
* Data entry.  

Question 02
-----------  
|Tid|    <b>Items bought</b>         |
|:-:|:------------------------------:|
| 10|              Beer, Nuts, Diaper|
| 20|      Beer, Coffee, Diaper, Nuts|
| 30|              Beer, Diaper, Eggs|
| 40|          Beer, Nuts, Eggs, Milk|
| 50|Nuts, Coffee, Diaper, Eggs, Milk|  
Table 1: Transactions from a database.  

Given the transaction in Table 1 and minsup s = 50%, how many frequent 3-itemsets are there?  

### Answer  
0  

### Explanation  
There are no frequent 3-itemsets by the minsup criterion alone.  

Question 03
-----------  
|Tid|    <b>Items bought</b>         |
|:-:|:------------------------------:|
| 10|              Beer, Nuts, Diaper|
| 20|      Beer, Coffee, Diaper, Nuts|
| 30|              Beer, Diaper, Eggs|
| 40|          Beer, Nuts, Eggs, Milk|
| 50|Nuts, Coffee, Diaper, Eggs, Milk|  
Table 1: Transactions from a database.  

A strong association rule satisfies both the minsup and minconf thresholds. Given the transactions in Table 1, minsup s = 50%, and minconf c = 50%, how many strong association rules are there? Note that the association rule A => B and B => A are distinct.  

### Answer  
6  

### Explanation  
Frequent itemsets: minsup = 50%  
Freq. 1-itemsets: Beer: 4, Nuts: 4, Diaper: 4, Eggs: 3  
Freq. 2-itemsets: {Beer, Diaper}: 3  
Association rules: minconf = 50%  
Beer => Diaper (60%, 75%)  
Diaper => Beer (60%, 75%)  
Beer => Nuts (60%, 75%)  
Nuts => Beer (60%, 75%)  
Diaper => Nuts (60%, 75%)  
Nuts => Diaper (60%, 75%)  

Question 04
-----------  
|Tid|    <b>Items bought</b>         |
|:-:|:------------------------------:|
| 10|              Beer, Nuts, Diaper|
| 20|      Beer, Coffee, Diaper, Nuts|
| 30|              Beer, Diaper, Eggs|
| 40|          Beer, Nuts, Eggs, Milk|
| 50|Nuts, Coffee, Diaper, Eggs, Milk|  
Table 1: Transactions from a database.  

Given the transactions in Table 1, minsup s = 50%, and minconf c = 50%, which of the following is an association rule? Select all that apply.  

### Answer  
* Beer => Nuts  
* Nuts => Diaper  

### Explanation  
Refer to previous question's explanation.  

Question 05
-----------  
Consider the database containing the transaction T1 : {a1, ..., a5}, T2 : {a1, ..., a1}, T3 : {a3, ..., a7}, T4 : {a4, ..., a8}. For what value of minsup do we have the most number of closed frequent patterns?  

### Answer  
minsup = 1  

Question 06
-----------  
Consider the database containing the transactions T1 : {a1, ..., a3}, T2 : {a2, ..., a4}. Let minsup = 1. What fraction of all frequent patterns is max frequent patterns?  

### Answer  
2/11  

### Explanation  
1-itemsets: {a1}:1, {a2}:2, {a3}:2, {a4}:1  
2-itemsets: {a1, a2}:1, {a2, a3}:2, {a1, a3}:1, {a2, a4}:1, {a3, a4}:1  
3-itemsets: {a1, a2, a3}:1, {a2, a3, a4}:1  
max frequent patterns: {a1, a2, a3}, {a2, a3, a4}  
closed frequent patterns: {a1, a2, a3}, {a2, a3, a4}, {a2, a3}  

Question 07
-----------  
Consider the database containing the transaction T1 : {a1, a2, a3}, T2 : {a2, a3, a4}. Let minsup = 1. What fraction of all frequent patterns is closed?  

### Answer  
3/11  

### Explanation  
Refer to previous question's explanation.  

Question 08
-----------  
Rank the following sets by their cardinality for a given database: {all frequent patterns}, {closed frequent patterns}, {max frequent patterns}  

### Answer  
{all frequent patterns} >= {closed frequent patterns} >= {max frequent patterns}  

Question 09
-----------  
Which of the following statements is true?  

### Answer  
We can recover all frequent patterns from the set of closed frequent patterns.  

### Explanation  
Closed pattern is a lossless compression of frequent patterns.   

Question 10
-----------  
If we know the support of itemset {a, b, c} is 10, which of the following numbers are the possible supports of the itemset {a, b}?  

### Answer  
* 10  
* 11  

### Explanation  
* Apriori: Any subset of a frequent itemset must be frequent and vice versa.  

Question 11
-----------  
If we know the support of itemset {a, b} is 10, which of the following numbers are the possible supports of itemset {a, b, c}?  

### Answer  
* 9  
* 10  

### Explanation  
* Apriori: Any subset of a frequent itemset must be frequent and vice versa.  

Question 12
-----------  
If we know the support of itemset {a} is 50, and the support of itemset {a, b, c} is 10, which of the following numbers are the possible supports of itemset {a, d}?  

### Answer  
* 5  
* 50  
* 30  
* 10  

Question 13
-----------  
Considering Apriori Algorithm, assume we have 5 items (A to E) in total. In the 1-st scan, we find out all frequent items A, B, C, and E. How many size-2 (i.e. containing 2 items, e.g. A, B) itemsets should be considered in 2-nd scan, i.e. are potential to be size-2 frequent itemsets?  

### Answer  
6  

### Explanation  
The Potential size-2 frequent itemsets are:  
* {A, B}
* {A, C}
* {A, E}
* {B, C}
* {B, E}
* {C, E}  

Question 14
-----------  
Considering Apriori Algorithm, assume we have obtained all size-2 (i.e. containing 2 items, e.g. {A, B}) frequent itemsets. They are {A, B}, {A, C}, {A, D}, {B, C}, {B, E}, {C, E}. In the following size-3 itemsets, which of them should be considered, i.e. are potential to be size-3 frequent itemsets?  

### Answer  
* {A, B, C}  
* {B, C, E}  

Question 15
-----------  
![alt text](https://github.com/UtkarshPathrabe/Pattern-Discovery-In-Data-Mining/blob/master/In%20Lecture%20Quizzes/Lecture%203.5.png "Mask")  
Figure 1: FP Tree  

Given the FP-tree as shown in Figure 1, what is the support of {c, p}?  

### Answer  
3  