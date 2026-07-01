import math

while True:

    print("\n========== BASIC CALCULATOR ==========")
    print("1. Addition")
    print("2. Subtraction")
    print("3. Multiplication")
    print("4. Division")
    print("5. Remainder")
    print("6. Square Root")
    print("7. Power")
    print("8. Absolute Value")
    print("9. Maximum of Two Numbers")
    print("10. Minimum of Two Numbers")
    print("11. Average of Two Numbers")
    print("12. Percentage")
    print("13. Cube")
    print("14. Cube Root")
    print("15. Exit")

    choice = int(input("\nEnter your choice (1-15): "))

    if choice == 15:
        print("Thank you for using the calculator!")
        break

    elif choice == 1:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        print("Answer =", a + b)

    elif choice == 2:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        print("Answer =", a - b)

    elif choice == 3:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        print("Answer =", a * b)

    elif choice == 4:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))

        if b != 0:
            print("Answer =", a / b)
        else:
            print("Cannot divide by zero!")

    elif choice == 5:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        print("Remainder =", a % b)

    elif choice == 6:
        a = float(input("Enter a number: "))
        if a >= 0:
            print("Square Root =", math.sqrt(a))
        else:
            print("Square root of a negative number is not possible.")

    elif choice == 7:
        a = float(input("Enter base: "))
        b = float(input("Enter power: "))
        print("Answer =", a ** b)

    elif choice == 8:
        a = float(input("Enter a number: "))
        print("Absolute Value =", abs(a))

    elif choice == 9:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        print("Maximum =", max(a, b))

    elif choice == 10:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        print("Minimum =", min(a, b))

    elif choice == 11:
        a = float(input("Enter first number: "))
        b = float(input("Enter second number: "))
        print("Average =", (a + b) / 2)

    elif choice == 12:
        total = float(input("Enter the total value: "))
        percent = float(input("Enter the percentage: "))
        print(percent, "% of", total, "=", (percent / 100) * total)

    elif choice == 13:
        a = float(input("Enter a number: "))
        print("Cube =", a ** 3)

    elif choice == 14:
        a = float(input("Enter a number: "))
        print("Cube Root =", a ** (1/3))

    else:
        print("Invalid choice! Please enter a number between 1 and 15.")
