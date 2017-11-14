# Hangman-Game1
#hangman game
#Hangman Game...

import random
dict=open("sözlük.txt", "r" )
#print(dict.readlines())
a=[i for i in dict]
#print(a)
list(a)
#print(*list(a))
b=random.choice(list(a))
print(b)
intro="""
~~~~~~~~~~~~~~~~~~~~~~~~
Wellcome to Hangman Game
~~~~~~~~~~~~~~~~~~~~~~~~
"""
print(intro)
table=[]
for i in range(len(b)-1):
    table.append("_")
print(*table)
while True:
    user=input("Give me ur letter")
    if user in b:





