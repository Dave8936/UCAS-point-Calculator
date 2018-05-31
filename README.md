# UCAS-point-Calculator
Still needs some work

var1 = [""""A*A*","112","A*","104","AA","96","AB","88","BB",80,"BC","72","CC","64","CD,"56"""]

var3 = [""""D*D*D*","168","D*D*D","160","D*DD","152","DDD","144","DDM","128","DMM","112","MMM,"96"""]


print("A Level" + " " + "or" + " " + "BTEC Level 3?")

chosen_course = input()


if   chosen_course == 'A Level':
     print('What grade did you get for your subjects?')
     print(var1)
     print("What was your first grade A Level?")
     grade1 = input()
     print("What was your second grade A Level?")
     grade2 = input()
     print("What was your third grade A Level?")
     grade3 = input()
     print(int(grade1) + int(grade2) + int(grade3))
       
elif chosen_course == 'BTEC Level 3':
     print('What grade did you get for your subjects?')
     print(var3)
     print("What was your first grade A Level?")
     grade1 = input()
     print("What was your second grade A Level?")
     grade2 = input()
     print("What was your third grade A Level?")
     grade3 = input()
     print(int(grade1) + int(grade2) + int(grade3))

else:
    print('Please Select a correct operation!')

