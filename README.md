# python
finding a number at correct position
def shuffle_list(my_list):
    shuffle(my_list)
    return my_list
result=shuffle_list(example)
my_guess=['','5','']
shuffle_list(my_guess)
def player_guess():
    guess=''
    
    while guess not in['0','1','2']:
        guess=input("Enter the guess index:0,1,2")
        
    return int(guess)
def check_guess(my_guess,guess):
    if my_guess[guess] =='5':
        print("Correct")
    else:
        print("Wrong")
        print(my_guess)
my_guess=['','5','']
mixed_list=shuffle_list(my_guess)
guess=player_guess()
check_guess(mixed_list,guess)
