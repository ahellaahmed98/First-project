print('welcome to my island!')
print('there are two doors in front of you.🚪a red door and 🚪a blue door')
door = input('wich door do you want to open ?\n')
if door == 'blue':
  print('Oops! you chose the crocodile door.\nGame over🐊🐊🐊')
elif door == 'yellow':
  print('invalid choice🤷‍♂️♂️🤷‍♂️♂️🤷‍♂️♂️')
elif door == 'red':
  print('you found there boxes: 🎁white, 🎁black, 🎁green')
  box = input('which box do you open?\n')
  if box == 'WHITE'.upper():
    print('Oops! you opend a box filled with snakes🐍🐍🐍')
  elif box == 'blue':
    print('invaild choice !🤷‍♂️♂️🤷‍♂️♂️🤷‍♂️♂️')
  elif box == 'black':
    print('Oops! you opend a box filld with spider🕷️🕷️🕷️')
  elif box == 'green':
    print('congratulations! you found the treasure!💰💰💰')
  else:
    print('sorry')
