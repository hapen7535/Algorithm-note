# map()
- map(function, iterable)
  - iterable : 반복 가능한 자료형 ex)list, tuble
  - function : 변환 양식을 포함한 함수
- 여러 개의 데이터를 한 번에 다른 형태로 변환  

다음과 같은 코드가 대표적인 예시  

```python
numbers = map(int, input().split())
```
input().split() 리스트가 되므로 map() 적용이 가능하다
