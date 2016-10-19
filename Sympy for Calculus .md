

```python
import os
```


```python
os.getcwd()
```




    'C:\\Users\\user\\Desktop\\ipython'




```python
from sympy import *
```


```python
x, y, z = symbols('x, y, z')
```


```python
EX1 = sqrt(1-x)
limit(EX1,x,-8)
```




    3




```python
limit(EX1,x,2)  #如果是不再函數的定義範圍內，Sympy似乎用I來表示不存在的結果
```




    I




```python
EX2 = (x**3-2*x+4)/(x**2+1)
limit(EX2,x,3)
```




    5/2




```python

```
