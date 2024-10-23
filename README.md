# EXNO-5-DS-DATA VISUALIZATION USING MATPLOT LIBRARY
# Name: V MYTHILI
# DEPT: CSE
# DATE: 23.010.24
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
```
import matplotlib.pyplot as plt

#create data for plotting
x_values = [0, 1, 2, 3, 4, 5]
y_values = [0, 1, 4, 9, 16, 25]

#The default graph style for plot is a line
plt.plot(x_values, y_values)

plt.show()
```


```
import matplotlib.pyplot as plt
x = [1,2,3]
y = [2,4,1]
#plotting the points
plt.plot(x,y)
# naming the x axis
plt.xlabel('x - axis')
# naming the y axis
plt.ylabel('y - axis')
# giving title to the graph
plt.title('My first graph!')
plt.show()
```

![image](https://github.com/user-attachments/assets/73790046-d4a7-4657-a489-170fbe0db7d9)

```
import matplotlib.pyplot as plt
x1=[1,2,3]
y1=[2,4,1]
plt.plot(x1,y1,label="line 1")

x2=[1,2,3]
y2=[4,1,3]
plt.plot(x2,y2, label="line 2")

plt.xlabel('x - axis')
plt.ylabel('y - axis')

plt.title('Two lines on same graph!')

plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/9d00797f-059a-4e45-b5e5-2b32f39e5f98)
```
import matplotlib.pyplot as plt
x=[1,2,3,4,5,6]
y=[2,4,1,5,2,6]

plt.plot(x,y, color='green', linestyle='dashed', linewidth=3, marker='o', markerfacecolor='blue', markersize=12)
plt.ylim(1,8)
plt.xlim(1,8)

plt.xlabel('x - axis')
plt.ylabel('y - axis')

plt.title('Some cool customization!')

plt.show()
```
![image](https://github.com/user-attachments/assets/de5498e2-060d-482e-a621-c91ddaaff02d)

```
yield_apples = [0.895, 0.91, 0.919, 0.926, 0.929, 0.931]
plt.plot(yield_apples)
```
![image](https://github.com/user-attachments/assets/87cb7b37-8b9e-4f46-b180-41e504a35832)

```
years = [2010,2011,2012,2013,2014,2015]
yield_apples = [0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years, yield_apples)
```
![image](https://github.com/user-attachments/assets/c2cb7ed6-feeb-4528-aa59-a172aa41d964)

```
import matplotlib.pyplot as plt
years = range(2000, 2012)
apples = [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges = [0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Years')
plt.ylabel('Yield (tons per hectare)');
```
![image](https://github.com/user-attachments/assets/9f6c43ea-4782-48e4-a6aa-44ca8b9e97af)

```
plt.plot(years, apples)
plt.plot(years, oranges)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)')
plt.title("Crop Yields in Kanto")
plt.legend(['Apples', 'Oranges']);
```
![image](https://github.com/user-attachments/assets/a391bd12-9a15-4809-a66a-9df6b0ee6111)

```
import matplotlib.pyplot as plt
years = [2010,2011,2012,2013,2014,2015]
yield_apples = [0.895,0.91,0.919,0.926,0.929,0.931]
plt.plot(years, yield_apples)
plt.xlabel('Year')
plt.ylabel('Yield (tons per hectare)');
```
![image](https://github.com/user-attachments/assets/49d6068c-7709-49ae-be1b-40ff9f68b821)

```
years = range(2000, 2012)
apples = [0.895,0.91,0.919,0.926,0.929,0.931,0.934,0.936,0.937,0.9375,0.9372,0.939]
oranges = [0.962,0.941,0.930,0.923,0.918,0.908,0.907,0.904,0.901,0.898,0.9,0.896]
plt.figure(figsize=(12, 6))
plt.plot(years, oranges, marker='o')
plt.title('Yield of oranges (tons per hectare)');
```

![image](https://github.com/user-attachments/assets/d1e910a5-f7bf-49f1-8708-26e5442d2a04)

```
plt.plot(years, apples, marker='o')
plt.plot(years, oranges, marker='x')

plt.xlabel('Years')
plt.ylabel('Yield (tons per hectare)')

plt.title("crop Yields in Kanto")
plt.legend(['Apples', 'Oranges'])
```
![image](https://github.com/user-attachments/assets/ea12f9e7-7408-4229-b8c7-124c2369e010)

```
import matplotlib.pyplot as plt
x_values = [0,1,2,3,4,5]
y_values = [0,1,4,9,16,25]
plt.scatter(x_values, y_values, s=30, color="blue")
plt.show()
```
![image](https://github.com/user-attachments/assets/84d49df2-1df3-451d-8e25-a3791f41c55f)

```
import matplotlib.pyplot as plt
x = [1,2,3,4,5,6,7,8,9,10]
y = [2,4,5,7,6,8,9,11,12,12]
plt.scatter(x, y, label="stars", color="green", marker="*", s=30)
plt.xlabel('x - axis')
plt.ylabel('y - axis')
plt.title('My scatter plot!')
plt.legend()
plt.show()
```
![image](https://github.com/user-attachments/assets/25d2dcaa-81b2-47ff-801b-aaf0839d825b)


```
import matplotlib.pyplot as plt
import numpy as np
import pandas as pd

x=np.arange(0,10)
y=np.arange(11,21)

x
```

![image](https://github.com/user-attachments/assets/af4ddfa6-dc97-4dc6-b86c-64a99ff60ea4)

```
y
```

![image](https://github.com/user-attachments/assets/c282648b-dbef-4fbc-8f90-8e1ccdd7c7ca)

```
plt.scatter(x,y,c='r')
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title('Graph in 2D')
plt.savefig('Test.png')

```

![image](https://github.com/user-attachments/assets/bbfb91f0-1cb5-4c9c-9205-172a4127c549)

```
y=x*x
y
```

![image](https://github.com/user-attachments/assets/5a6bbd15-2cd5-48c7-aa35-b7888cdd41d6)

```
plt.plot(x,y,'g*',linestyle='dashed',linewidth=2,markersize=12)
plt.xlabel('x axis')
plt.ylabel('y axis')
plt.title('2D diagram')
```

![image](https://github.com/user-attachments/assets/5c11abb7-35e5-43db-af4a-6ac332ebe256)


```
plt.subplot(2,2,1)
plt.plot(x,y,'r--')
plt.subplot(2,2,2)
plt.plot(x,y,'g*--')
plt.subplot(2,2,3)
plt.plot(x,y,'bo')
plt.subplot(2,2,4)
plt.plot(x,y,'go')
```

![image](https://github.com/user-attachments/assets/48eefe21-87df-430a-b6bc-eb3c4b0ee861)

```
np.pi
```

![image](https://github.com/user-attachments/assets/8ae91d8d-8d1f-4af6-b791-8abd3d14fa9a)


```
x = np.arange(0, 4 * np.pi, 0.1)
y = np.sin(x)
plt.title("sine wave form")
plt.plot(x,y)
plt.show()
```

![image](https://github.com/user-attachments/assets/1d0bf496-c09e-45ed-9076-65ba5bd0dbb9)

```
import matplotlib.pyplot as plt
import numpy as np
x = [1,2,3,4,5]
y1 = [10,12,14,16,18]
y2 = [5,7,9,11,13]
y3 = [2,4,6,8,10]
plt.fill_between(x,y1,color='blue')
plt.fill_between(x,y2,color='green')
plt.plot(x,y1,color='red')
plt.plot(x,y2,color='black')
plt.legend(['y1','y2'])
plt.show()
```


![image](https://github.com/user-attachments/assets/909c7bf3-6051-4480-9dbe-c581be5d50ae)

```
plt.stackplot(x,y1,y2,y3,labels=['Line 1','Line 2','Line 3'])
plt.legend(loc='upper left')
plt.title('Stacked Line Chart')
plt.xlabel('X axis')
plt.ylabel('Y axis')
plt.show()
```

![image](https://github.com/user-attachments/assets/f97df86f-c288-4f11-a6d1-00d97a3674de)

```
import numpy as np
import matplotlib.pyplot as plt
from scipy.interpolate import make_interp_spline
x = np.array([1,2,3,4,5,6,7,8,9,10])
y = np.array([2,4,5,7,8,8,9,10,11,12])
spl = make_interp_spline(x,y)
x_smooth = np.linspace(x.min(),x.max(),100)
y_smooth = spl(x_smooth)
plt.plot(x,y,'o',label='data')
plt.plot(x_smooth,y_smooth,'-',label='spline')
plt.legend()
plt.show()
```

![image](https://github.com/user-attachments/assets/a6263a40-25f0-426f-a2d8-cff84b82a7d1)

```
import matplotlib.pyplot as plt
values = [5,6,3,7,2]
names = ["A", "B", "C", "D", "E"]
plt.bar(names, values, color="green")
plt.show()
```

![image](https://github.com/user-attachments/assets/c8745ca8-0fd8-4a81-83a9-933014101956)


# Result:

 Include your result here
