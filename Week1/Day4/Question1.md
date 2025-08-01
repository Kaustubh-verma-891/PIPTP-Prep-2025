## Find the output of the following pseudocode


### Pseudocode:
```java
public static int calc(int n) {
    if (n <= 2) return n;
    return calc(n- 1) * calc(n-2);
}

System.out.println(calc(5));
```
---
### Output: `8`

- Note: Rather finding the output of 5 directly, start calculating value of function from 0 to 5.