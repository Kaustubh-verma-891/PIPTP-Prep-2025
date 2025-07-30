## Find the output of the following pseudocode

### Pseudocode:

```
function printUp(n):
    if n == 0:
        return
    printUp(n - 1)
    print(n)
printUp(3)
```

---

### Python code:

```python
def printUp(n):
    if n == 0:
        return
    printUp(n-1)
    print(n)

printUp(3)
```

### Output: `1 2 3`