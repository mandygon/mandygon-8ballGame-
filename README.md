# mandygon-8ballGame-
game = """   
          888     BBBBB     AAA     L      L
        8     8   B    B  A     A   L      L
        8     8   B    B  A     A   L      L
          888     BBBB B  AAAAAAA   L      L
        8     8   B    B  A     A   L      L
        8     8   B    B  A     A   L      L
          888     BBBBB   A     A   LLLLL  LLLL
"""


print(game)





import random 
# Declare a variable and assign it to a name of a person
name = input("What is your name? ")

# Declare a another variable with your question
question = input("Ask a question... ")

# Store the answer from the Magic ball in another variable
answer = ""

# We need to use a random utility like .randint(), but first we need to import the module so we can use its functions 


random_number = random.randint(1,10)


if random_number == 1:
  answer= "Yes - definitely."
elif random_number == 2: 
  answer= "It is decidedly so."
elif random_number == 3: 
  answer= "Without a doubt."
elif random_number == 4: 
  answer= "Reply hazy, try again."
elif random_number == 5: 
  answer= "Ask again later."
elif random_number == 6: 
  answer = "Better not tell you now."
elif random_number == 7: 
  answer = "My sources say no."
elif random_number == 8: 
  answer = "Outlook not so good."
elif random_number == 9:
  answer= "Very doubtful."
elif random_number == 10: 
  answer = "Signs point to yes"
else: 
  answer = "Error"

print(name + " ask: " + question)
print("Magic 8-Ball's answer: " + answer) 
