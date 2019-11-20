---
title:  "Jekyll Theme: Next"
date:   2019-11-20 10:10:50 +0800
categories:
tags: 
- Next
description: Next主题的使用说明
---

# test

- test
- test
- test
- test

---



## 代码高亮测试

```python
import requests

def getHTMLText(url):
    try:
        r = requests.get(url, timeout=30)
        r.raise_for_status() # 如果状态不是200，引发HTTPError异常
        r.encoding = r.apparent_encoding
        return r.text
    except:
        print("HTTP Error")

if __name__ == "__main__":
    url = "http://www.baidu.com"
    print(getHTMLText(url))
```



---

## 图片测试

![avatar](assets/2019-11-20-jekyll-next-theme/avatar.jpg)