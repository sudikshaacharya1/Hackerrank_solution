#!/bin/python3

import math
import os
import random
import re
import sys

#
# Complete the 'plusMinus' function below.
#
# The function accepts INTEGER_ARRAY arr as parameter.
#

def plusMinus(arr):
    n1=len(arr)
    p=0
    n=0
    z=0
    for num in arr:
        if num>0:
            p=p+1
        elif num<0:
            n=n+1
        else:
            z=z+1
    print(p/n1)
    print(n/n1)
    print(z/n1)
    
if __name__ == '__main__':
    n = int(input().strip())

    arr = list(map(int, input().rstrip().split()))

    plusMinus(arr)
