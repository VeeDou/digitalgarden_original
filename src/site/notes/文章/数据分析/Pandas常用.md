---
{"dg-publish":true,"permalink":"/文章/数据分析/Pandas常用/"}
---

---
# 1. 初始化
```python
import pandas as pd import numpy as np
# 1.1 通过“列表”初始化：列表可以是：等长的numpy多维数组、等长的多维的list 
dates = pd.date_range('20190728', periods=3)
df1 = pd.DataFrame(np.random.randn(3, 4), index=dates, columns=list('ABCD')) 
```python
#1.2 通过“列表”组成的字典初始化：等长的numpy多维数组、等长的多维的list 
data = {'A':{'20190728':1,'20190729':1,'20190730':1}, 
'B':{'20190728':2,'20190729':2,'20190730':2},
 'C':{'20190728':3,'20190729':3,'20190730':3},
 'D':{'20190728':4,'20190729':4,'20190730':4} } 
#通过 columns指定获取数据的列和顺序（显式列索引 > 数据列索引） 
df2 = pd.DataFrame(data,columns = ['D','C','B']) 
```
# 2. 切片

# 3. 合并
# 4. 聚合
# 5. 行列转置

---
创建时间:2023-02-05 22:56
内容链接: 
1.  

