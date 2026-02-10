# Python-Program-to-Print-Fibonacci-Series-Using-Iteration-Correct-Code
a = 0
b = 1

n = int(input("Enter the number of terms in the sequence: "))

print(a, b, end=" ")

for i in range(n - 2):
    c = a + b
    print(c, end=" ")
    a, b = b, c

Output:
Enter the number of terms in the sequence: 7
0 1 1 2 3 5 8
