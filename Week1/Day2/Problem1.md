## Find the output of the following pseudocode

### Pseudocode:

```
Integer a, b, c
Set a = 2, b = 6, c = 8
a = (10 + 9) + c
if ((c+b) > (a-c))
    a = b+c
    b = b+b
End if
Print a+b+c
```

---

### Python code:

```python
a, b, c = 2, 6, 8
a = (10+9) + c
if (c+b) > (a-c):
    a = b+c
    b = b+b
print(a+b+c)
```
---

- Initial values: `a = 2`, `b = 6`, `c = 8`
- Final values: `a = 27`, `b = 6`, `c = 8`

### Output: `41`