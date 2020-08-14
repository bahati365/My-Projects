import random

while True:
    print('make a choice:')
    choice = input()
    choice = choice.lower()
    print("My choice is", choice)

    choices = ['rock', 'paper', 'scissors']
    computer_choice = random.choice(choices)
    print("computer choice is", computer_choice)

    if choice in choices:
        if choice == computer_choice:
            print('it is a tie')
            break

        if choice == 'rock':
            if computer_choice == 'paper':
                print('you lose :(')
            elif computer_choice == 'scissors':
                print('you win!!! :))')

        if choice == 'paper':
            if computer_choice == 'scissors':
                print('you lose :(')
            elif computer_choice == 'rock':
                print('you win!!! :))')

        if choice == 'scissors':
            if computer_choice == 'rock':
                print('you lose :(')
            elif computer_choice == 'paper':
                print('you win!!! :))')
    else:
        print('unsupported choice, try again with either rock, paper or scissors')

    print()









