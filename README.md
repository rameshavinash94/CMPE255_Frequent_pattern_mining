# Write a colab to demonstrate frequent pattern mining apriori and fpgrowth


Dataset: Market Basket Optimisation
Link: https://www.kaggle.com/dragonheir/basket-optimisation

**Association Rule Mining:**
Association Rule Learning is rule-based learning for identifying the association between different variables in a database. One of the best and most popular examples of Association Rule Learning is the Market Basket Analysis

### **Apriori**
The algorithm was first proposed in 1994 by Rakesh Agrawal and Ramakrishnan Srikant. Apriori algorithm finds the most frequent itemsets or elements in a transaction database and identifies association rules between the items

To construct association rules between elements or items, the algorithm considers 3 important factors which are, support, confidence and lift. Each of these factors is explained as follows:

**Support:**
The support of item I is defined as the ratio between the number of transactions containing the item I by the total number of transactions


**Confidence:**
This is measured by the proportion of transactions with item I1, in which item I2 also appears. The confidence between two items I1 and I2, in a transaction is defined as the total number of transactions containing both items I1 and I2 divided by the total number of transactions containing I1

**Lift:**
Lift is the ratio between the confidence and support.

### **FP-Growth**
FP-Growth is an algorithm for extracting frequent itemsets with applications in association rule learning that emerged as a popular alternative to the established Apriori algorighm.

The reason why FP Growth is so efficient is that it’s a divide-and-conquer approach.
Since FP-Growth doesn't require creating candidate sets explicitly, it can be magnitudes faster than the alternative Apriori algorithm.
