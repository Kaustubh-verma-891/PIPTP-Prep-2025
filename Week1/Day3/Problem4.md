## Find the output of the following pseudocode

### Pseudocode:

```
function sumDown(n, total):
    if n == 0:
        print(total)
        return
    sumDown(n - 1, total + n)
    print(n)

sumDown(3, 0)
```

---

### Python code:

```python
def sumDown(n,total):
    if n == 0:
        print(total)
        return
    sumDown(n-1,total + n)
    print(n)

sumDown(3,0)
```
---

### Output: `6 1 2 3`