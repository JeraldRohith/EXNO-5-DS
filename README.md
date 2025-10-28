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

# Coding:
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

# Output:

<img width="732" height="545" alt="image" src="https://github.com/user-attachments/assets/f1052dff-802b-46bb-ba6d-c82b209c27fd" />


```
student=['A','B','C','D']
attendence=[90,85,73,88]
plt.plot(attendence,student)
plt.xlabel('Attendence')
plt.ylabel('Student name')
plt.show()

```

# Output:


<img width="703" height="540" alt="image" src="https://github.com/user-attachments/assets/f32ed950-9eb8-444b-8103-2d4003719c24" />


```
x=[10,20,30,40,50]
y=[100,200,300,400,500]
plt.scatter(x,y,label='stars',color='green',marker='*',s=30)
plt.show()

```

# Output:


<img width="699" height="530" alt="image" src="https://github.com/user-attachments/assets/6c238882-fc08-457d-8859-933137f569d3" />

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

# Output:


<img width="710" height="572" alt="image" src="https://github.com/user-attachments/assets/c4d5b1b7-6c29-49bf-8ab8-ed84eb82a3e6" />


```
act=['eat','sleep','work','play']
slices=[3,7,8,6]
color=['r','y','g','b']
plt.pie(slices,labels=act,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```

# Output:


<img width="573" height="532" alt="image" src="https://github.com/user-attachments/assets/2cea2cff-69a3-49b4-addf-d1845485b035" />


```
feedback=['Good','excellent','Perfect','Ok']
slices=[4,10,3,8]
color=['y','r','b','g']
plt.pie(slices,labels=feedback,colors=color,startangle=90,shadow=True,explode=(0.1,0.1,0.1,0.1),radius=1.2,autopct='%1.1f%%')
plt.legend()
plt.show()

```

# Output:


<img width="604" height="531" alt="image" src="https://github.com/user-attachments/assets/a4fb7cc8-9c9c-4c44-b763-981f7fccf595" />


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

# Output:


<img width="720" height="537" alt="image" src="https://github.com/user-attachments/assets/8b9cb23e-2fd6-4d66-ac73-69dc5b0e08e1" />


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

# Output:


<img width="730" height="587" alt="image" src="https://github.com/user-attachments/assets/2ea05f83-2a81-4019-b803-f575b041b83c" />


```
x = [2,1,6,4,2,4,8,9,4,2,4,10,6,4,5,7,7,3,2,7,5,3,5,9,2,1]
plt.hist(x, bins = 10, color='blue', alpha=0.5)
plt.show()

```
# Output:


<img width="676" height="516" alt="image" src="https://github.com/user-attachments/assets/d0b990fe-ebf4-48d3-87ac-5b3268e586d6" />


```
np.random.seed(0)
data=np.random.normal(loc=0, scale=1, size=100)
data

```

# Output:


<img width="800" height="453" alt="image" src="https://github.com/user-attachments/assets/405d48d5-eac7-42f8-8c0b-2f12892b6ead" />


```
fig, ax= plt.subplots()
ax.boxplot(data)
ax.set_xlabel('Data')
ax.set_ylabel('Values')
ax.set_title('Box Plot')

```

# Output:


<img width="717" height="575" alt="image" src="https://github.com/user-attachments/assets/6ba561cf-429b-474b-87fe-20f3e885a887" />


# Result:
Thus, all the data visualization techniques of matplotlib has been implemented.
