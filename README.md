# Decision-Tree-Random-Forest--Documentation
Decision Tree: Hierarchical model for classification and regression, partitioning data based on feature values.Random Forest: Ensemble method combining multiple decision trees to enhance accuracy and mitigate overfitting, ideal for diverse datasets.

# Decision Tree & Random Forest 01

* Sample dataset used in classification<br><br>
![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/98193c27-05e0-48fa-ba17-ecae822cdaf4)

* What is Decision Trees

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/201bb4cc-45ff-4f9c-a253-34768fa89552)

* Decision Tree structure

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/f46b05f7-84a3-4432-8937-a13c57c14e96)


* Univariate Decision trees and Multivariate Decision tree
  
![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/ccb6ce7d-6967-4753-affe-00123c45ffbe)

* Binary Decision Trees and N-ary Decision Trees

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/9ed0a8b0-6f3c-4c80-9c00-36331b6480cb)

* Attribute Selection Measure
1. Attribute Selection Measure
2. Gain Ratio (used in C4.5 Algorithm)
3. Gini Index (used in CART algorithm)

* Entropy

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/2e6d2d92-ed5b-469f-9a10-8cba64c960a1)

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/6430ac41-7d80-4f27-9966-acbf2b7a4a6c)

* Entropy of parent – Entropy of the entire dataset
* To calculate that should consider dependent variable (buy mobile phone or not) – 
* Calculate how many time class label “yes” has been accord and
* Calculate how many time class label “no” has been accord in entire data set in here 10 data set. 
* Yes = 6 time accord , No = 4 times.
* So calculate Entropy of a node :


![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/690449fd-ac7c-4b57-8806-da792f7664a2)

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/ec72a361-3b1c-4cf1-a63e-ac0e55f489ed)
![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/b61d3674-4d37-4d2f-91fe-1f3246b7836a)
![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/9309b76e-a53b-4666-9e0d-4e14c4552e15)<br>
So the calculation – <br><br>
![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/4cfb5183-1486-4271-919e-a0c3802b75c4)
![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/d5f57c8e-7954-4b0c-a761-079e69282227)<br><br>

* For that we get Age class and calculate weighted average of the entropy.
* In Age class – 3 class types, so consider each class at once.
* Check one by one those three classes.

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/68283297-e595-4017-b889-b28f1ca7e70c)

Now apply this information to our equation 

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/cc19efc5-5963-4d64-a3d2-b905a38a8946)<br><br>

Compute information gain of each attribute (Age class, income level, profession)

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/eb9fac04-0b00-422e-81c8-b367b0e5fc11)
<br><br>

Why take highest -  The weight of entropy small mean that data set is more pure. So the different is high mean the weight average entropy is small. So always get pure data set. 

![image](https://github.com/778569/Decision-Tree-Random-Forest--Documentation/assets/52319671/775acfe1-f89d-4a44-8f0c-0ef3994104db) <br><br>

*Among Age class and income level which one base on split?*
<b>*So you should calculate the entropy value again and again*</b>

# Decision tree Pruning (Document 03)

![image](https://github.com/778569/Decision-Tree-Documentation/assets/52319671/695d2903-3f64-47f9-a27f-e959bf845f03) <br><br>

1.	Pre-pruning
2.	Post-pruning(backward pruning)
![image](https://github.com/778569/Decision-Tree-Documentation/assets/52319671/338f5892-7ccf-47e8-a2c4-3e002e3c2921) <br><br>

Rule Extraction from Decision Tree

# Model validation 




