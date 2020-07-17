#guess the number

#no of guesses
#print number of guess left
#game over



'''no=18


print("you can attempt for 5 times")
i=0
total=5
while i<total:
  guessno=int(input("Guess your number:"))
  if guessno<no:
    print("enter a large number than your choice.")
   
  elif guessno>no:
    print("enter a smaller number than your choice")
  elif guessno==no:
    print("you got the correct number.")
    break
  else:
    print("Game Over.")
i=i+1
print(,"no of guesses left")'''

n=18
number_of_guesses=1
print("Number of guesses is limited to only 9 times: ")
while (number_of_guesses<=9):
    guess_number = int(input("Guess the number :\n"))
    if guess_number<18:
        print("you enter less number please input greater number.\n")
    elif guess_number>18:
        print("you enter greater number please input smaller number.\n ")
    else:
        print("you won\n")
        print(number_of_guesses,"no.of guesses he took to finish.")
        break
    print(9-number_of_guesses,"no. of guesses left")
    number_of_guesses = number_of_guesses + 1

if(number_of_guesses>9):
    print("Game Over")

    


