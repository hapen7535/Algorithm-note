# zip()
- 여러 개의 iteratable(반복가능한 객체)를 parameter로 받는다
- parameter를 연결하여 하나의 tuple로 만들어준다
- parameter가 여러 개 일시, 가장 짧은 parameter를 기준으로 데이터가 서로 연결된다
  - 더 긴 parameter는 연결되지 못하고 버려진다
```python
numbers = [1, 2, 3]
alphabets = ["A", "B"]
sequence = list(zip(numbers, alphabets))
```
위와 같은 코드를 시행할 경우, sequence에는 [(1, 'A'), (2, 'B')]만 들어가게 된다.  
numbers의 3은 버려지게 된다.
  
- zip()으로 묶어놓은 데이터를 분리할 때도 zip()을 사용하여 분리할 수 있다.
- zip()을 적용한 데이터에 zip() 다시 적용하면, 분리된 데이터를 얻을 수 있다.

```python
numbers = [1, 2, 3]
alphabets = ["A", "B"]
sequence = list(zip(numbers, alphabets))
numbers, alphabets = zip(*sequence)
```

참고 : 
- <a href="https://docs.python.org/3/library/functions.html#zip">Python docs</a>
- <a href="https://www.daleseo.com/python-all/">DaleSeo</a>
