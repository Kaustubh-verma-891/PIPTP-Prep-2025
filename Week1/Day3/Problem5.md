## Find the output of the following pseudocode

### PseudoCode:

```
array = [10, 20, 30, 40]
function reversePrint(i):
    if i == length(array):
        return
    reversePrint(i + 1)
    print(array[i])

reversePrint(0)
```
---
### Python Code:

```python
array = [10, 20, 30, 40]
def reversePrint(i):
    if i == length(array):
        return
    reversePrint(i + 1)
    print(array[i])

reversePrint(0)
```

### Output: `40 30 20 10`