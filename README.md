# Small-tools
#Delete space from pdf to word 
import sys
f1=open(r"10.txt","r")
for A in f1.readlines():
    A=A.strip("\n")
    print (A,end=" ")
