# Recursion

![image](https://user-images.githubusercontent.com/23376002/166132381-9a7eb0b2-ec40-413b-87a6-ff8d0897364b.png)

![image](https://user-images.githubusercontent.com/23376002/166134204-d13561b6-3d97-4557-8798-f3aebb4de7ec.png)

![image](https://user-images.githubusercontent.com/23376002/166134813-5704f457-b8ee-4c01-bb24-9e4e50824b33.png)

![image](https://user-images.githubusercontent.com/23376002/166134826-9c2d8535-1858-438f-9ca5-bf220dea2532.png)

![image](https://user-images.githubusercontent.com/23376002/166135482-134d9677-8a17-4d90-a685-26cefbb507b3.png)


### Multiple Recursion calls :
Calling simultaneously multiple recursive functions
- e.g Nth fibonacci number problem


```java
int fib(int n)
{
    if(n<=1)
        return 1;
    return fib(n-1) + fib(n-2);
}

```

### Recursion on Subsequences :

![image](https://user-images.githubusercontent.com/23376002/166149593-2534f42e-e774-416c-8828-5e3ad1594125.png)


