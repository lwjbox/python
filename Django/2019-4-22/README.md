# 1. django项目实现
### URL配置，view视图，templates模板（html页面），models模块（数据库）
![flow1](1.png)
```python
from __future__ import unicode_literals
from django.db import models


class Article(models.Model):
    title = models.CharField(max_length=32, default='Title')
    content = models.TextField(null=True)
```
![flow1](2.png)
![flow1](3.png)
![flow1](4.png)
![flow1](5.png)
![flow1](6.png)
