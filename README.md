print("Welcome to Matrix world.\nYour mission is to survive by making life chocies")
c1=input("which pill do you wanna choose red or blue?").lower()
if c1=="red":
    print("\n\nCongratulations for moving to next round")
    print("It will be a matter of time in which human's will make a bad desicon and kill themselves!!! ")

    c2=int(input("You will now receive matrix world currency.\nDo you want 2 Milliom now if yes press 1.\nIf you want a penny now that will double everyday for 30 days press 2."))
    print("\n\nBeen a month and matrix is back to take you back to matrix world")
    if c2==1:
        print("You chose 2 million dollar")
    elif c2==2:
        print("Your penny is now worth 5 millions")
    else:
        print("You dumb humans like always made dumb choice and got killed")
      
      
    print("\n\nNow you have the money power only the richest will survive at the end\n\n")
    c3=int(input("You can buy  3 options things:- \n1.A 2 million car\n2.A house worth 2m.\n3. Gold "))
    if c3==1:
        print("Dumb you got killed the car is now worth less than a million")
    elif c3==1:
        print("You made a great choice house in now worth 5 million")
    elif c3==3:
        print("FInally a smart human to invest smartly you are the richest now.")
    else:
        print("You dumb human like always made wrong choice and got killed")
else:
   print ("You dumb human like always made wrong choice and got killed")
