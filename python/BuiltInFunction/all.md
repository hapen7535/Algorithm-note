# all()
- 인자로 넘어온 모든 요소가 True일 때만 True를 return
- 인자가 boolean 타입일 필요 없다
- boolean이 아닌 값이나 식(expression)은 내부적으로 boolean으로 형변환
- 요소들을 boolean으로 형변환 한 다음, True/False 여부를 판단

```python
all([1, "TEST", 1 < 2, 2 + 3 == 5]) # True
```

위 코드는 모든 값, 식이 boolean으로 변환됐을 때, 모두 True이므로 True가 return된다.

출처 : <a href="https://www.daleseo.com/python-all/">DaleSeo</a>
