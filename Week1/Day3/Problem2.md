## Find the output of the following pseudocode

### Pseudocode:

```
function mystery(n):
    if n == 0:
        return
    mystery(n - 1)
    mystery(n - 1)
    print(n)
mystery(2)
```

---

### Python code:

```python
def mystery(n):
    if n == 0:
        return
    mystery(n-1)
    mystery(n-1)
    print(n)

mystery(2)
```

---

### Output: `1 1 2`