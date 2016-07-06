while word:
  position = random.randrange(len(word))
  jumble += word[position]
  word = word[:position] + word[(position + 1):]


print ("The jumble is:", jumble)
guess = input("Your guess: ")
guess = guess.lower()

if guess==correct:
    print ("Correct")
else:
    print ("Wrong")
