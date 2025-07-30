## Evaluate f(5). What familiar function does f compute?

### Code:

```python
def f(n):
    if n == 0:
        return 1
    else:
        return g(n,f(n-1))

def g(a,b):
    if b == 0:
        return 0
    else:
        return a + g(a, b - 1)

print(f(5)) 
```

---

### Output: 120
---
### Note:

This function is similar to the function to find factorial of a number.

We can dry run the function by taking value of n from 0 to n and find pattern which shows factorial of n.