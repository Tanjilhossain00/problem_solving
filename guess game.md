# code
import random
print('To stop anytime ,enter press q')
score=0
while True:
    num=random.randint(0,10)
    guess=input('Guess a number between 0 and 10:')
    if str(guess)=='q':
        print('Game over')
        print(f'your score is :{score}')
        break
    if int(guess)==num:
        print('Congrates Your guess number is correct')
        score+=10
        print(f'your score is {score}')
    else:
        print('Your guess number is not correct')
        print(f'This number was {num}')
