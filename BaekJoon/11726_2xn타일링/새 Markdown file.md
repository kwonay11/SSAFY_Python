다 세어보아서 점화식을 구하는 dp문제이다.

N = 1 일 때 1

N = 2 일 때 2

N = 3 일 때 3

N = 4 일 때 5

N = 5 일 때 8

이므로 

**점화식 dp[i] = dp[i-1]+dp[i-2]**

