# Python - condition operator

## is

```python
1 is 1
```

a is b 에서 a와 b의 레퍼런스를 비교합니다.

하지만 a is b (but b <= 256) 의 경우에는 == 처럼 보입니다.

본래 id(a) == id(b) 와 같은 개념인데 크기가 257을 넘어가면 id 값이 달라집니다.

이에 대해서는 int object의 메모리 할당 원리를 봐야할 것 같습니다.