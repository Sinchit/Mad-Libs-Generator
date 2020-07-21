# Mad-Libs-Generator
#The Goal: Inspired by Summer Son’s Mad Libs project with Javascript. 
#The program will first prompt the user for a series of inputs a la Mad Libs. 
#For example, a singular noun, an adjective, etc. 
#Then, once all the information has been inputted, the program will take that data and place them into a premade story template. 
#You’ll need prompts for user input, and to then print out the full story at the end with the input included.

list_noun=[]
list_verb=[]
list_adjective=[]
list_adverb=[]

for i in range(0,3):
    list_noun.append(input("Please enter a noun : "))

for i in range(0,4):
    list_adjective.append(input("Please enter a adjective : "))

for i in range(0,3):
    list_verb.append(input("Please enter a verb(past tense) : "))

for i in range(0,2):
    list_adverb.append(input("Please enter a adverb : "))


print("Today I went to the zoo. I saw a(n) ___{}___(adjective)___{}___(Noun) jumping up and down in its tree.\
He ___{}___(verb, past tense) ___{}___(adverb) through the large tunnel that led to its ___{}___(adjective)\
___{}___(noun). I got some peanuts and passed them through the cage to a gigantic gray ___{}___(noun) towering above my head.\
Feeding that animal made me hungry. I went to get a ___{}___(adjective) scoop of ice cream. It filled my stomach.\
Afterwards I had to ___{}___(verb) ___{}___ (adverb) to catch our bus. When I got home I ___{}___(verb, past tense) my\
mom for a ___{}___(adjective) day at the zoo.".format(list_adjective[0],list_noun[0],list_verb[0],list_adverb[0],list_adjective[1],
    list_noun[1],list_noun[2],list_adjective[2],list_verb[1],list_adverb[1],list_verb[2],list_adjective[3] ))
