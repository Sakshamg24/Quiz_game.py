print("Welcome to my computer quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("Okay! Let's play :)")
score = 0

answer = input("What does Oops stand for? ")
if answer.lower() == "object oriented programming":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does Dsa stand for? ")
if answer.lower() == "data structure and algorithm":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does DAA  stand for? ")
if answer.lower() == "design and analysis of algorithm":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

answer = input("What does OS in cse stand for? ")
if answer.lower() == "operating System":
    print('Correct!')
    score += 1
else:
    print("Incorrect!")

print("You got " + str(score) + " questions correct!")
print("You got " + str((score / 4) * 100) + "%.")
