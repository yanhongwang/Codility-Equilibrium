def solution(A):
    # write your code in Python 2.7
    LenA = len(A)
    
    if sum(A[1:LenA]) == 0:
        return 0
    
    for Index in xrange(1, LenA - 1):
        if sum(A[:Index]) == sum(A[Index+1:LenA]):
            return Index
    
    if sum(A[:LenA-1]) == 0:
        return LenA - 1
    
    return -1
