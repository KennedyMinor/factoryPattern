def display_info(animal):
    if animal == "Cat":
        print("Number of lives: 9")
    elif animal == "Dog":
        breed = input("Enter the breed of the dog: ")
        print(f"The breed of the dog is {breed}")
    else:
        print("Invalid choice. Please select either 'Cat' or 'Dog'.")

def main():
    while True:
        print("\nMenu:")
        print("1. Select Cat")
        print("2. Select Dog")
        print("3. Exit")
        
        choice = input("Enter your choice (1/2/3): ")
        
        if choice == '1':
            display_info("Cat")
        elif choice == '2':
            display_info("Dog")
        elif choice == '3':
            break
        else:
            print("Invalid choice. Please select 1, 2, or 3.")

if __name__ == "__main__":
    main()
