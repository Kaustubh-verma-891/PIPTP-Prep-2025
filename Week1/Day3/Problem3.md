## Find the output of the following pseudocode

### Pseudocode:

```
function loopRec(n):
    if n == 0:
        return
    for i = 1 to 2:
        loopRec(n - 1)
    print(n)

loopRec(2)
```
---

### Python code:

```python
def loopRec(n):
    if n == 0:
        return
    for i in range(1,3):
        loopRec(n-1)
    print(n)

loopRec(2)
```

---

### Output: `1 1 2`