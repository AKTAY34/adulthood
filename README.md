def age_classifier():
    try:
        age = int(input("How old are you? "))

        if age >= 18:
            print("You are an adult.")
        elif 12 <= age < 18:
            print("You are a teenager.")
        elif 4 <= age < 12:
            print("You are a child.")
        elif 0 <= age < 4:
            print("You are a baby.")
        else:
            print("Invalid age. Age cannot be negative.")
    except ValueError:
        print("Please enter a valid number.")

if __name__ == "__main__":
    age_classifier()
