# any()
- 반복가능한 자료형(iteration) 중 하나라도 True이면 True를 return
- 모든 요소가 False여야 False를 return
- iteration이 비어있으면, False를 반환

```python
def any(iterable):
    for element in iterable:
        if element:
            return True
    return False
```
any()는 내부적으로 위와 같이 구현돼있다.

출처 : <a href="https://docs.python.org/3/library/functions.html#all">Python docs</a>
