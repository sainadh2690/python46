# python46
n= int(input("Enter the number"))
for i in range(n):
    for j in range(n):
        if i==j or i==n-1 or j==0:
            print("*", end=' ')
        else:
            print(" ", end=" ")
    print()
