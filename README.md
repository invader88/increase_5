# increase_5
print("Addition of 5 to 3 numbers you enter...")
input("If ok, press RETURN ")
i = 0
j = 0
k = 0
while i == 0:
    try:
        a = int(input("Enter the first number : "))
        i += 1
    except ValueError:
        print("It's not a number. Try again ")
first = a
while j == 0:
    try:
        b = int(input("Enter the second number: "))
        j += 1
    except ValueError:
        print("Look better, you made it wrong again. Enter a number ")
second = b
while k == 0:
    try:
        c = int(input("Enter the third number: "))
        k += 1
    except ValueError:
        print("Not number. Enter a number: ")
third = c
if first == second or second == third or first == third:
    first = first+5
    second = second+5
    third = third+5
    print("All three numbers are increased by 5. " + "\n" + "See them below: ")
    print("First = {}".format(first) + "\n" + "Second = {}".format(second) + "\n" + "Third = {}".format(third))
else:
    print("No two equal numbers found")
    

