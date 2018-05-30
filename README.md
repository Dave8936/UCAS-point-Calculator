# UCAS-point-Calculator
Still needs some work

var1 = ["A*A*","A*","AA","AB","BB","BC","CC","CD  ,112,104,96,88,80,72,64,56"]

var3 = ["D*D*D*","D*D*D","D*DD","DDD","DDM","DMM","MMM ,168,160,152,144,128,112,96"]

print("A Level" " " + "or" + " " "BTEC Level 3?")

chosen_course = input()


if   chosen_course == 'A Level':
     print('What grade did you get for your subjects?')
     print(var1)
     
elif chosen_course == 'BTEC Level 3':
     print('What grade did you get for your subjects?')
     print(var3)
else:
    print('Please Select a correct operation!')

print("What was your first grade A Level?")
grade1 = input()
print("What was your second grade A Level?")
grade2 = input()
print("What was your third grade A Level?")
grade3 = input()

results = (grade1 + grade2 + grade3)
print(results)


print("What was your first grade BTEC Level 3?")
grade1 = input()
print("What was your second grade BTEC Level 3?")
grade2 = input()
print("What was your third grade BTEC Level 3?")
grade3 = input()

results2 = (grade1 + grade2 + grade3)
print(results2)
