Write a simple application using a recursive function that accepts a value (integer) and returns the fibonacci value at that position in the series.
The application should be performant at scale to handle larger numbers without slowing down exponentially.

1. START by following command node fibonacci.js

2. Input the non-negative integer ‘n’

3. If (n===1)

        return [0, 1];

    else

        return  fibonacci_series(n - 1).push(fibonacci_series(n - 1)[fibonacci_series(n - 1).length - 1] + fibonacci_series(n - 1)[fibonacci_series(n - 1).length - 2]);

4. Print, nth Fibonacci number

5. END
