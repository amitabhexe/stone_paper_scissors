rock = '''
    _______
---'   ____)
      (_____)
      (_____)
      (____)
---.__(___)
'''

paper = '''
    _______
---'   ____)____
          ______)
          _______)
         _______)
---.__________)
'''

scissors = '''
    _______
---'   ____)____
          ______)
       __________)
      (____)
---.__(___)
'''
import random
rand1 = random.randint(1,3)

rps = int(input("Choose 1.Rock/ 2.Paper/ 3.Scissors\nType input as 1/2/3: "))
print("You Chose: ")
if rps==1:
    print(rock)
elif rps==2:
    print(paper)
else:
    print(scissors)

print("Computer chose: ")
if rand1==1:
    print(rock)
elif rand1==2:
    print(paper)
else:
    print(scissors)

if(rps==rand1):
    print("Tie!")
if(rps==1 and rand1 == 2):
    print("You Lose!!!")
if(rps==1 and rand1 == 3):
    print("You Win!!!")
if(rps==2 and rand1 == 1):
    print("You Win!!!")
if(rps==2 and rand1 == 3):
    print("You Lose!!!")
if(rps==3 and rand1 == 1):
    print("You Lose!!!")
if(rps==3 and rand1 == 2):
    print("You Win!!!")
