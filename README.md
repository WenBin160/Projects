# Projects

# A simple code for number factorial, input a number and its factorial will be outputted

n = int(input("Number you want to Factorial: "))

total = 1
for i in range(1, n+1):
    total *= i


print(total)
