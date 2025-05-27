# Anurag-start-of-coding
#sorting hat
#i love coding this answer
#print('I am the biggest fan of Harry potter')
print('==============')
print('Sorting Hat')
print('==============')
Gryffindor=0
Ravenclaw=0
Hufflepuff=0
Slytherin=0
print('Q1) Do you like Dawn or Dusk?')
print('    1) Dawn')
print('    2) Dusk')
Answer=int(input('Enter your answer 1-2: '))
if Answer==1:
  Gryffindor+=1 # Gryffindor=Gryffindor+1
  Ravenclaw+=1
elif Answer==2:
  Hufflepuff+=1
  Slytherin+=1
else:
  print('Wrong input')
print('Q2) When I’m dead, I want people to remember me as:')
print('    1) The Good')
print('    2) The Great')
print('    3) The Wise')
print('    4) The Bold')
Answer=int(input('Enter your answer 1-4:  '))
if Answer==1:
  Hufflepuff+=2 # Hufflepuff=Hufflepuff+2
elif Answer==2:
  Slytherin+=2
elif Answer==3:
  Ravenclaw+=2
elif Answer==4:
  Gryffindor+=2
else:
  print('Wrong input')
print('Q3) Which kind of instrument most pleases your ear?')
print('    1) The violin')
print('    2) The trumpet')
print('    3) The piano')
print('    4) The drum')
Answer=int(input('Enter your answer 1-4:  '))
if Answer==1:
  Slytherin+=4
elif Answer==2:
  Hufflepuff+=4
elif Answer==3:
  Ravenclaw+=4
elif Answer==4:
  Gryffindor+=4
else:
  print('Wrong Input')
print('The number of score for Gryffindor is:', Gryffindor)
print('The number of score for Slytherin is:', Slytherin)
print('The number of score for Hufflepuff is:', Hufflepuff)
print('The number of score for Ravenclaw is:', Ravenclaw)
if Gryffindor>Ravenclaw and Gryffindor>Hufflepuff and Gryffindor>Slytherin:
  print('Gryffindor has scored the highest points')
elif Ravenclaw>Hufflepuff and Ravenclaw>Slytherin:
  print('Ravenclaw has scored the highest points')
elif Hufflepuff>Slytherin:
  print('Hufflepuff has scored the highest points')
else:
  print('Slytherin has scored the highest points')
