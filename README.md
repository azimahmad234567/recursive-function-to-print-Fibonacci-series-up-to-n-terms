# recursive-function-to-print-Fibonacci-series-up-to-n-terms
def fibonacci(n):
    if n == 0:
        return 0
    elif n == 1:
        return 1
    else:
        return fibonacci(n - 1) + fibonacci(n - 2)

terms = 6
for i in range(terms):
    print(fibonacci(i), end=" ")
