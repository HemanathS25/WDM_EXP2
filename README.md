### EX2 Generating Association Rules for Transaction dataset using Apriori Algorithm
### DATE: 24/04/2026
### AIM: To generate associate rules for the Transaction dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Transaction Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation Transaction
@attribute Tid {T100,T200,T300,T400,T500,T600,T700,T800,T900}
@attribute I1 {yes,no}
@attribute I2 {yes,no}
@attribute I3 {yes,no}
@attribute I4 {yes,no}
@attribute I5 {yes,no}
@data
T100,yes,yes,no,no,yes
T200,no,yes,no,yes,no
T300,no,yes,yes,no,no
T400,yes,yes,no,yes,no
T500,yes,no,yes,no,no
T600,no,yes,yes,no,no
T700,yes,no,yes,no,no
T800,yes,yes,yes,no,yes
T900,yes,yes,yes,no,no
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:

<img width="486" height="360" alt="image" src="https://github.com/user-attachments/assets/e21aa6f6-ab49-4301-927d-8da1e516596d" />

### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
<img width="1091" height="972" alt="image" src="https://github.com/user-attachments/assets/44e13673-600d-4eb0-9db0-0058d4b97543" />


### RESULT: 
Thus the associative rule for transaction data set is executed successfully.
