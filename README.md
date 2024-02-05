# Simple Python script for a basic command-line application

def main():
    print("Welcome to Simple Application!")
    print("Please choose an option:")
    print("1. Display a message")
    print("2. Exit")

    choice = input("Enter your choice (1 or 2): ")

    if choice == '1':
        display_message()
    elif choice == '2':
        print("Exiting the application...")
    else:
        print("Invalid choice. Please enter either '1' or '2'.")

def display_message():
    print("Hello, World! This is a simple application.")

if __name__ == "__main__":
    main()
