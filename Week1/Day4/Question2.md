## Find the output of the pseudocode

### Pseudocode:

```java
public static int solve(int a, int b) {
    if (b == 0) return a;
    return solve(b, a % b);
}

System.out.println(solve(48, 18));
```

---

### Output: `6`


**This is the function to find GCD of two numbers.**