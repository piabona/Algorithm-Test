- 영어 알파벳으로 이루어진 문자열 str이 주어집니다. 각 알파벳을 대문자는 소문자로 소문자는 대문자로 변환해서 출력하는 코드를 작성해 보세요.

```python
print(input().swapcase())
```

```python
print(''.join(x.upper() if x == x.lower() else x.lower() for x in input())
```

```python
str = input()

for i in str : 
    if i.isupper() : 
        print(i.lower(), end='')
    else : 
        print(i.upper(), end='')
```

출처 : https://school.programmers.co.kr/learn/courses/30/lessons/181949 
