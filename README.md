# copy-
l1=[1,2,3,4]
l1 # oupput [1, 2, 3, 4]
l1.append(100)
l1 # output [1, 2, 3, 4, 10, 100]
import copy
l2=l1.copy()
l2 # output [1, 2, 3, 4, 10, 100]
