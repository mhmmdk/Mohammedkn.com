# Solution for Google code Jam.
## 2019
---
```python
for i in range(1,int(input())+1):
    a = input()
    b = int(a.replace('4', '2'))
    a = int(a) - b
    print("Case #{}: {} {}".format(i, a, b))   
```
---
```python
for i in range(1,int(input())+1):
    input()
    moves = input().replace('E', 'W')
    moves = moves.replace('S', 'E').replace('W', 'S')
    print("Case #{}: {}".format(i, moves))   
``` 
---
