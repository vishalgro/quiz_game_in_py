# quiz_game_in_py
print("welcome to the game")
playing = input("Do you want to play? (yes/no): ").strip().lower()

if playing  != "yes":
    print("Exiting the game. Goodbye!")
    quit()
point = 0
answer = input("What is the cpu stand? ").strip().lower()
if answer == "central processing unit":
    print("Correct!")
    point += 1
else:
    print("Incorrect! The correct answer is 'central processing unit'.")

    
answer = input("What is the gpu? ").strip().lower()
if answer == "graphics processing unit":
    print("Correct!")
    point += 1
else:
    print("Incorrect! The correct answer is 'graphics processing unit'.")

    
answer = input("What is the ram? ").strip().lower()
if answer == "random access memory":
    print("Correct!")
    point = point + 1
else:
    print("Incorrect! The correct answer is 'random access memory'.")

    
answer = input("What is the psu stand? ").strip().lower()
if answer == "power supply unit":
    print("Correct!")
    point += 1
else:
    print("Incorrect! The correct answer is 'power supply unit'.")

print(f"You got {point} out of 4 questions correct.")
