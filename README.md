# 70.-Climbing-Stairs
Hints: Recursive, dynamic programming, fibonacci way as related to 1 and 2

```C#
       public class Solution {
    int[] a = new int[1000];
    public int ClimbStairs(int n) {
        
        a[0]=1;
        a[1]=1;
        
        if(a[n] != 0){
            return a[n];
        }
       a[n] = ClimbStairs(n - 1) + ClimbStairs(n - 2);
        
        return a[n];
        
    }
}
```

## Complexity Analysis

* Time Complexity: O(n)
* Space Complexity: O(n)

Solution 2: 

```C#
       public class Solution {
    int[] a = new int[1000];
    public int ClimbStairs(int n) {
        
        a[0]=1;
        a[1]=1;
        
        if(a[n] != 0){
            return a[n];
        }
       a[n] = ClimbStairs(n - 1) + ClimbStairs(n - 2);
        
        return a[n];
        
    }
}
```
## Complexity Analysis

* Time Complexity: O(n)
* Space Complexity: O(n)
