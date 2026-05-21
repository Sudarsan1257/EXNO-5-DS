# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY

# Aim:
  To Perform Data Visualization using matplot python library for the given datas.

# EXPLANATION:
Data visualization is the graphical representation of information and data. By using visual elements like charts, graphs, and maps, data visualization tools provide an accessible way to see and understand trends, outliers, and patterns in data.

# Algorithm:
STEP 1:Include the necessary Library.

STEP 2:Read the given Data.

STEP 3:Apply data visualization techniques to identify the patterns of the data.

STEP 4:Apply the various data visualization tools wherever necessary.

STEP 5:Include Necessary parameters in each functions.

# Coding and Output:
```import pandas as pd
 import numpy as np
 import seaborn as sns
 import matplotlib.pyplot as plt
```

```
 marks=[13,45,63,78]
 student=['ABC','QOR','EFB','TOB']
 plt.plot(marks,student)
 plt.xlabel('Marks')
 plt.ylabel('Student name')
 plt.show()
```
<img width="1022" height="723" alt="image" src="https://github.com/user-attachments/assets/f32686d3-0dd9-4d28-b3b7-5a221ccbccb3" />

```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
<img width="803" height="591" alt="image" src="https://github.com/user-attachments/assets/3b08f65c-2645-4ef3-9d46-a4e0776d810b" />


```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
```
<img width="855" height="535" alt="image" src="https://github.com/user-attachments/assets/4675dbf0-60c5-469e-bcba-750fb87002fd" />

```
 x=np.arange(0,15)
 y=np.arange(0,15)
 x
 y
 plt.scatter(x,y,c='r')
 plt.xlabel('X axis')
 plt.ylabel('y axis')
 plt.title('Scatter plot')
 plt.show()
```
<img width="986" height="667" alt="image" src="https://github.com/user-attachments/assets/572047a3-80cd-4006-bfb3-46645c527a37" />

```
 act=['eat','sleep','work','play']
 slices=[3,7,8,6]
 color=['r','y','g','b']
 plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
 plt.legend()
 plt.show()
```
<img width="1161" height="592" alt="image" src="https://github.com/user-attachments/assets/bd2249e3-9e47-4003-964a-e2280f1a0c5a" />

```
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="1266" height="549" alt="image" src="https://github.com/user-attachments/assets/9dbdb4ee-6063-4740-841a-738f363ee0bc" />

```
x = [1, 2, 3, 4, 5]
y1 = [10, 12, 14, 16, 18]
y2 = [5, 7, 9, 11, 13]
y3 = [2, 4, 6, 8, 10]
plt.fill_between(x, y1, color='blue')
plt.fill_between(x, y2, color='green')
plt.plot(x, y1, color='red')
plt.plot(x, y2, color='black')
plt.legend(['y1','y2'])
plt.show()
```
<img width="888" height="645" alt="image" src="https://github.com/user-attachments/assets/e7a705f9-d3a1-405b-902d-0a3b7aa8e569" />

```
height = [10, 24, 36, 40, 5]
names = ['one', 'two', 'three', 'four', 'five']
c1=['red', 'green']
c2=['b', 'g']
plt.bar (names, height, width=0.8, color=c1)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My bar chart!')
plt.show()
```
<img width="894" height="670" alt="image" src="https://github.com/user-attachments/assets/9096c153-4cc4-4bda-937f-5a4756074fdf" />

```
 x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
<img width="731" height="502" alt="image" src="https://github.com/user-attachments/assets/4882195b-7311-4b1b-b98f-97d38461de5b" />

```
 np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
<img width="827" height="488" alt="image" src="https://github.com/user-attachments/assets/5560b45c-4093-4b33-b199-56517343c353" />

```
 fig, ax= plt.subplots()
 ax.boxplot(data)
 ax.set_xlabel('Data')
 ax.set_ylabel('Values')
 ax.set_title('Box Plot')
```
<img width="785" height="620" alt="image" src="https://github.com/user-attachments/assets/c23b4af5-fa83-4876-bb25-aad384c83ab7" />

# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
