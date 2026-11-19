# luffy-rubber-simulator
gum gum stretch with luffy
import random

secret = random.randint(1, 10)
guess = int(input("Guess a number between 1 and 10: "))

if guess == secret:
  print("You got it!")
else:
  print(f"Nope, the number was {secret}.")
