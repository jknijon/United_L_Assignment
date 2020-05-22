# Hotel Program
person_name=input('Enter your name:\n')
budget=input('Enter your budget:\n')
if int(budget) <= 2000:
    print("The rooms available cost around Rs.1900 includes TV,couch and table\n")
elif int(budget) > 2000 and int(budget) <=5000:
    print("The rooms available cost around Rs.3500 includes TV,couch,butler service and table\n")
elif int(budget) > 5000 and int(budget) <=10000:
    print("The rooms available cost around Rs.9500 includes TV,couch,butler service,AC,mini bar and table\n")
else:
    print("Budget below 10,000")

