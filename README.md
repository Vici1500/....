# Starta ColabTurtle och rita koordinataxlar.
initializeTurtleWithAxis()
iso = False
pieni = False
print("Minkä kokoinen?")
size = input("1=Iso 2=Pieni: ")
size = int(size)
if size == 1:
  print("Piirretään isoa...")
  iso = True
elif size == 2:
  print("Piirretään pientä...")
  pieni = True
else:
  print("Valitettavasti emme tunnistaneet vastaustasi")

if iso == True:
  penup()
  goto(-100, -150)
  pendown()
  goto(-100, 0)
  goto(0,0)
  goto(0,-150)
  goto(-100,-150)
  goto(100,-150)
  goto(100,0)
  goto(0,0)
  goto(-50,0)
  goto(-50,200)
  goto(50,200)
  goto(50,0)
  penup()
  goto(-50,150)
  pendown()
  goto(50,150)
  penup()
  goto(0,150)
  pendown()
  goto(0,200)
if pieni == True:
  print("Isommat on paremia")
