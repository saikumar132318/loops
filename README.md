# loops1

for i in range(10):
    print(i)



#loops2nd program

A='Program'

for i in A:
    print(i)

#using while loop

num = int(input("Enter a number: "))
fact = 1
i = 1

while i <= num:
    fact *= i
    i += 1

print("The factorial of", num, "is", fact)


#4th program

for i in range(0, 10, 2):
    print(i)
