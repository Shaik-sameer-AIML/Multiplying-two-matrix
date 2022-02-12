#Developed By:shaik sameer
#Ref no : 21003881
import numpy as np

m1,m2 =[],[]

n = int(input())

for i in range(n):

     m1.append(int (input()))

for i in range(n):
     m2.append(int (input()))
value1=np.array(m1)
value2= np.array(m2)

result = value1*value2


print("Product of two arrays is:", result)
