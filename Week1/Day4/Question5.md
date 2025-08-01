## If a linked list has 100 nodes, how many recursive calls will be made to compute sum?

### Code:

```java
int sum(Node head) {
    if (head == null) 
        return 0;
    return head.val + sum(head.next);
}
```

### Output: `101`