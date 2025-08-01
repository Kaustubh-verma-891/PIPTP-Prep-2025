## Find the output of the pseudocode for `X = AGGTAB` and `Y = GXTXAYB`

### Pseudocode:

```java
public static int solve(String x, String y, int m, int n) {
    if (m == 0 || n == 0) return 0;
    if (x.charAt(m-1) == y.charAt(n-1))
        return 1 + solve(x,y,m-1,n-1);
    else
        return Math.max(solve(x,y,m-1,n),solve(x,y,m,n-1));
}

System.out.println(solve("AGGTAB","GXTXAYB",6,7));
```

---

### Output: 4

**This function finds the length of longest common subsequence from the given two strings.**