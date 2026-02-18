# .Python-program-to-find-out-the-product-of-a-set-of-real-numbers.
product = 1
count = int(input("Enter the number of real numbers: "))

for i in range(count):
    x = float(input("Enter a real number: "))
    product = product * x

print("The product of the numbers is:", product)

Output:
Enter the number of real numbers: 3
Enter a real number: 2
Enter a real number: 1
Enter a real number: 3
The product of the numbers is: 6.0

