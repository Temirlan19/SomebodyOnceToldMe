# SomebodyOnceToldMe
Code wtih Russell 
import numpy as np
file=open ('hw1.txt')
x_val=np.array([])
for i in range(100):
    line=file.readline()
    x_val=np.append(x_val,line)
file.close()

x_val
