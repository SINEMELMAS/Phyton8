# Phyton8
def phone_number(char):
    if char in "ABC":
        return "2"
    elif char in "DEF":
        return "3"
    elif char in "GHI":
        return "4"
    elif char in "JKL":
        return "5"
    elif char in "MNO":
        return "6"
    elif char in "PQRS":
        return "7"
    elif char in "TUV":
        return "8"
    elif char in "WXYZ":
        return "9"
    else:
        return char
telephone_number = input("Enter a telephone number in the format XXX-XXX-XXXX: ")
converted_number = ""
for char in telephone_number:
    converted_number += phone_number(char)
print("New phone number is:", converted_number)
