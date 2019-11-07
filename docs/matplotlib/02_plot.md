# Plot

## plot funcion 
A simple plot function is availabel which can be used to rander a basic chart.
```python
import matplotlib.pyplot as plt
x = [i for i in range(10)]
y = [2*i for i in x]

plt.plot(x, y)
plt.xlabel("Unit")
plt.ylabel("Doubled")
plt.title("Sample Chart Using Plot function")
plt.show()
```
![01_linechart_01](./img/01_linechart_01.png)

## Figure instance
Alternate option is to use a figure instance.
```python
import matplotlib.pyplot as plt
x = [i for i in range(10)]
y = [2*i for i in x]

figure = plt.figure()
chart = figure.add_axes([0.1, 0.1, 0.8, 0.8])
chart.plot(x,y)
chart.set_xlabel("Unit")
chart.set_ylabel("Diubled")
chart.set_title("Sample Chart Using Figure")
plt.show()
```
![01_linechart_02](./img/01_linechart_02.png)