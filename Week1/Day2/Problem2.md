## Find the output of the following pseudocode for `a=0`, `b=2`, `c=10`

### PseudoCode:

```
Integer fun(Integer a, Integer b, Integer c)
    b = 7+a
    a = (a+c)+a
    b = (b+b)+c
    c = 1+b
    return a+b+c
End function fun()
```
---

### Python Code:

```python
def fun(a,b,c):
    b = 7+a
    a = (a+c)+a
    b = (b+b)+c
    c = 1+b
    return a+b+c

print(fun(0,2,10))
```

---

- Initial values: `a=0`, `b=2`, `c=10`
- Final values: `a=10`, `b=24`, `c=25`

### Output: `59`