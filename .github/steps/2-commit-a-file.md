import random 
num = random.randint(1,9)
input("Ask your question: ")
pos = 'Yes - definitely.', 'It is decidedly so.', 'Without a doubt'
ntrl = 'Reply hazy, try again.', 'Ask again later.', 'Better not tell you now.'
neg = 'My sources say no.', 'Outlook not so good.', 'Very doubtful.'
if num <= 3:
  print(random.choice(pos))
if num >= 4:
  print(random.choice(ntrl))
if num >= 6:
  print(random.choice(neg))
