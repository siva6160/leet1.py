# leet1.py
class Solution:
    def isPowerOfTwo(self, n: int) -> bool:
        p=0
        while True:
            if pow(2,p)==n:
                return True
            if pow(2,p)>n:
                return False
            p+=1
