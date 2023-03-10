# fibonacci-
1) Run by following command fibonacci.js

Recursive algorithm to get Fibonacci sequence:

1. START

2. Input the non-negative integer ‘n’

3. If (n===1)

        return [0, 1];

    else

        return  fibonacci_series(n - 1).push(fibonacci_series(n - 1)[fibonacci_series(n - 1).length - 1] + fibonacci_series(n - 1)[fibonacci_series(n - 1).length - 2]);

4. Print, nth Fibonacci number

5. END
