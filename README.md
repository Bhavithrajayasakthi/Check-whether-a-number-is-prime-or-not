# Check-whether-a-number-is-prime-or-not
def check_prime(num):
    if num <= 1:
        print(num, "is not a prime number")
        return

    for i in range(2, num):
        if num % i == 0:
            print(num, "is not a prime number")
            return

    print(num, "is a prime number")

n = int(input("Enter an integer: "))
check_prime(n)
output:
Enter an integer: 7
7 is a prime number
