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
*Frequent itemsets: minsup = 50%  
1. Freq. 1-itemsets: Beer: 4, Nuts: 4, Diaper: 4, Eggs: 3  
2. Freq. 2-itemsets: {Beer, Diaper}: 3
* Association rules: minconf = 50%  
1. Beer => Diaper (60%, 75%)  
2. Diaper => Beer (60%, 75%)  
3. Beer => Nuts (60%, 75%)  
4. Nuts => Beer (60%, 75%)  
5. Diaper => Nuts (60%, 75%)  
6. Nuts => Diaper (60%, 75%)  

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
