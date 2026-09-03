Exercise1 Output:
DFS
Enter the element to search using DFS: 20
Element found in BST using DFS.
BFS
Enter the element to search using BFS: 7
Element found in BST using BFS.

Exersice2 Output:
Start:  1 2 3 4 5 6 0 7 8
Goal:   1 2 3 4 5 6 7 8 0
--- A* Search ---
Steps to reach goal:
[1, 2, 3]
[4, 0, 5]
[6, 7, 8]
-----
[1, 2, 3]
[4, 5, 0]
[6, 7, 8]
-----
Total steps: 1
--- Memory-Bounded A* (IDA*) ---
Steps to reach goal:
[1, 2, 3]
[4, 0, 5]
[6, 7, 8]
-----
[1, 2, 3]
[4, 5, 0]
[6, 7, 8]
-----
Total steps: 1
Exercise3 Output:
Linear Regression:
MSE: 442.24
R² : 0.9278
Polynomial Regression (degree = 2):
MSE: 49.74
R² : 0.9919
<img width="681" height="423" alt="image" src="https://github.com/user-attachments/assets/1dc75c59-77db-40cb-8a66-a89197cae40c" />
Exercise4 Output:
First 5 rows of dataset:
sepal length (cm) sepal width (cm)  petal length (cm)  petal width (cm) species
0                5.1               3.5                1.4               0.2  setosa
1                4.9               3.0                1.4               0.2  setosa
2                4.7               3.2                1.3               0.2  setosa
3                4.6               3.1                1.5               0.2  setosa
4                5.0               3.6                1.4               0.2  setosa

Model Accuracy: 1.0

Classification Report:
               	Precision	recall	f1-score	support

  setosa       	1.00      	1.00     1.00        	19
  versicolor    1.00      	1.00     1.00        	13
  virginica    	1.00      	1.00     1.00        	13

  accuracy                           1.00		      45
  macro avg   	1.00		    1.00     1.00        	45
  weighted avg  1.00		    1.00     1.00		      45

<img width="975" height="517" alt="image" src="https://github.com/user-attachments/assets/828fb3e3-63ca-415b-801c-0370be6cf0aa" />
Exercise5 Output:
Sample Data:
   label                                               text
0   ham  Subject: enron methanol ; meter # : 988291\r\n...
1   ham  Subject: hpl nom for january 9 , 2001\r\n( see...
2   ham  Subject: neon retreat\r\nho ho ho , we ' re ar...
3  spam  Subject: photoshop , windows , office . cheap ...
4   ham  Subject: re : indian springs\r\nthis deal is t...

Model Accuracy: 0.9916237113402062

Classification Report:
               precision    recall  f1-score   support

         Ham       1.00      0.99      0.99      1121
        Spam       0.98      0.99      0.99       431

    accuracy                           0.99      1552
   macro avg       0.99      0.99      0.99      1552
weighted avg       0.99      0.99      0.99      1552

New Email Predictions:
'Congratulations! You've won a $1000 Walmart gift card. Click here to claim now.' → Spam
'Hi John, just wanted to confirm our meeting tomorrow at 10 AM.' → Ham





