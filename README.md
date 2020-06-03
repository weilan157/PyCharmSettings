# PyCharmSettings

## PyCharmSettings Template

```python
#!/usr/bin/env python3
# -*- coding:utf-8 -*-
"""
@Project :${PROJECT_NAME}
@IDE:     ${PRODUCT_NAME}
@file:    ${NAME}.py
@time:    ${DATE} ${TIME}
@user:    ${USER}
"""


class ${NAME}(object):
    """
    ${NAME}:
    """
    def __init__(self):
        super(${NAME}, self).__init__()
    
    def __del__(self):
        pass
    
    def start(self):
        """
        程序入口
        """
        try:
            pass
        except Exception as e:
            print(e)
        
        
if __name__ == "__main__":
    obj = ${NAME}()
    obj.start()
    del obj

```
