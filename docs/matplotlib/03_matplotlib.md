# MatplotLib

## Plot using function
```python
import matplotlib.pyplot as plt

x = [...]
y = [...]

plt.plot(x, y)
plt.xlabel('x label')
plt.ylable('y label')
plt.title('Plot of y vs x')
plt.show()
```

## Plot using Object oriented way
```python
import matplotlib.pyplot as plt

x = [...]
y = [...]

figure = plt.figure()
axes = figure.add_axs(xStart, yStart, xEnd, yEnd)
axes.set_xlabel('x label')
axes.set_ylabel('y label')
axes.set_title('Plot of y vs x')
axes.plot()
plt.show()
```

## Appearance
```python
plot(x, y, 
    color='#005588', 
    linewidth=2, 
    alpha=0.5, 
    linestyle='dashed', 
    marker='o', 
    markersize=12,
    markerfacecolor='yellow',
    markeredgecolor='#005588',
    markeredgewidth=2)
```

## References
 - [Matplotlib Gallery](https://matplotlib.org/gallery/index.html#text-labels-and-annotations)