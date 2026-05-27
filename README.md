# GK-quiz-game
Game using python 
print("Welcome to Computer Quiz")
playing= input("Do you want to play? ")
if playing.lower() !="yes":
    quit()
print("Okay! let's play :)")
score=0

answer = input("What does CPU stands for?:")
if answer.lower() =="central processing unit":
    print("Correct!")
    score+=1
else:
    print(" Sorry it's Wrong ._. The Correct answer is central processing unit")
    
answer=input("Who Invented Telephone? :")
if answer.lower()=="alexander graham bell":
    print("you're Absolutely correct!")
    score+=1
else:
    print("Sorry you're wrong")

answer = input("How many continents in the world?:")
if answer=="7":
    print("you're Absolutely correct!")
    score+=1

else:
    print("wrong")

answer = input("What does GPU stands for?:")
if answer.lower()=="graphics processing unit":
    print("you're Absolutely correct!")
    score+=1

else:
    print("wrong")

Name= input("What is your Name:")
if score == 4:
    print(Name,'you are a Beast')
else:
    print(Name,"Don't worry do better next time :)")
print(Name,"your score:",score)



