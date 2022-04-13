# guess a limit
secret = "12"
guess = input("Guess the number 1 - 20:")
guess_counter = 0
guess_limt = False

while guess != secret and not guess_limt:
    print("you have three gusses only")
    guess = input("Guess the number 1 - 20")
    guess_counter += 1 
    if guess == secret:
        print("you win!")
    else:
        guess_limt = True
print("you lose!")
