# yield
- return 과 비슷하게 결과값을 제공하는 키워드
- 제너레이터(enerator)를 반환
  - 제너레이터의 특성으로, 메모리에 한 번에 데이터를 올리기 부담스러울 때 사용된다
  
### yield from
- 리스트를 제너레이터로 변환할 수 있다
```python
def yield_abc():
  yield from ["A", "B", "C"]
```

참고 : <a href="https://www.daleseo.com/python-all/">DaleSeo</a>
