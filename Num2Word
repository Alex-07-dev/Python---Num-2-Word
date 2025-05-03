from num2words import num2words

while True:
    user_input = input("Enter a number (or 'q' to quit): ")
    if user_input.lower() == 'q':
        break
    try:
        number = float(user_input)
        print("In words:", num2words(number).capitalize())
    except ValueError:
        print("Invalid input. Please enter a valid number.")
