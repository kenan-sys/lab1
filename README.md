import math
x = 1.9
E = 0.001
sum_s = 1
term=1
n=1
while term > E:
    term = (x**n)/math.factorial(n)
    sum_s += term
    n += 1
print(sum_s)
