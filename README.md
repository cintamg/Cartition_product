# Cartition_product
To find the cartition product of the given lists.
from itertools import product
a=list(map(int,input().split()))
b=list(map(int,input().split()))
print(*product(a,b))
