# 2-3-2022-1
#program to print subtraction  of 2 matrices:

A=[]

m=int(input('enter no.of rows:'))

n=int(input('enter no.of columns:'))

for i in range(m):

    row=[]

    for j in range(n):

        k=int(input())

        row.append(k)

    A.append(row) 

print(A)    

B=[]

m=int(input('enter no.of rows'))

n=int(input('enter no.of columns:'))

for i in range(m):

    row=[]

    for j in range(n):

        k=int(input())

        row.append(k)

    B.append(row)

print(B)

result=[[0,0],[0,0]]

for i in range(m):

    for j in range(n):

        result[i][j]=A[i][j]-B[i][j]

print('resultant matrix is:')

for i in range(m):

    for j in range(n):

        print(result[i][j],end=' ')

    print()

    

    

    

   OUTPUT:

   enter no.of rows:2

enter no.of columns:2

10

9

8

7

[[10, 9], [8, 7]]

enter no.of rows2

enter no.of columns:2

1

2

34

4

[[1, 2], [34, 4]]

resultant matrix is:

9 7 

-26 3
