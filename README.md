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
 NAME: S DHANUSH
 REF NO: 25005353

import pandas as pd
import numpy as np
import seaborn as sns
import matplotlib.pyplot as plt

# Line Plot: 
```
marks=[13,45,63,78]
student=['ABC','QOR','EFB','TOB']
plt.plot(marks,student)
plt.xlabel('Marks')
plt.ylabel('Student name')
plt.show()
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()
```
<img width="829" height="548" alt="Screenshot 2025-10-28 151858" src="https://github.com/user-attachments/assets/b765b192-56ca-4d02-b9cf-fbc4cde52289" />
<img width="776" height="546" alt="Screenshot 2025-10-28 152016" src="https://github.com/user-attachments/assets/7a0b3b49-25b6-4ba7-b47b-5edeee3c7167" />

# Scatter Plot:
```
 x=[10,20,30,40,50]
 y=[100,200,300,400,500]
 plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
 plt.show()
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
<img width="728" height="527" alt="Screenshot 2025-10-28 152124" src="https://github.com/user-attachments/assets/374e59de-a717-43ee-82f0-7913c9a0999c" />
<img width="866" height="569" alt="Screenshot 2025-10-28 152141" src="https://github.com/user-attachments/assets/b8519254-b265-4fd7-802e-856e7030c07a" />

# Pie Chart:
```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()
```
<img width="649" height="535" alt="Screenshot 2025-10-28 152208" src="https://github.com/user-attachments/assets/5b253dc9-1a05-49c4-9b16-576ae9d751e7" />
<img width="704" height="521" alt="Screenshot 2025-10-28 152229" src="https://github.com/user-attachments/assets/c75e1390-f4a3-48be-9174-fe834ae9e439" />

# Area Chart:
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
<img width="791" height="521" alt="Screenshot 2025-10-28 152329" src="https://github.com/user-attachments/assets/3b2e9c4b-1822-45aa-adce-ec7aca204860" />

# Bar Chart:
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
<img width="889" height="570" alt="Screenshot 2025-10-28 152408" src="https://github.com/user-attachments/assets/8c556c9d-9b51-4639-a358-7fa1ed4db921" />

# Histogram:
```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
 plt.hist(x, bins = 10, color='blue', alpha=0.5)
 plt.show()
```
<img width="794" height="532" alt="Screenshot 2025-10-28 152424" src="https://github.com/user-attachments/assets/f9b7c99f-2ced-466d-9800-3cb5f7838004" />

# Box Plot:
```
np.random.seed(0)
 data=np.random.normal(loc=0, scale=1, size=100)
 data
```
<img width="776" height="450" alt="Screenshot 2025-10-28 152447" src="https://github.com/user-attachments/assets/8e4c7c05-2e05-4734-bd48-4a4494bfab33" />

```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')
plt.show()
```
<img width="809" height="578" alt="Screenshot 2025-10-28 152506" src="https://github.com/user-attachments/assets/68f60235-b4b8-4ba0-affc-94000233f1bf" />

# Result:
 Thus,all the data visualization techniques of matplotlib has been implemented.
