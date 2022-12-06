number_of_class_held=int(input('Number of class held:'))
attendence=int(input('Number of class Attendece day:'))
print('Did You have madical case?')
madical_case=input('Y/N: ')
attendence_rate=(attendence/number_of_class_held)*100
print('Attendece rate',round(attendence_rate),'%')

if attendence_rate>74:
    print('You are Allowed  in the exam')
elif attendence_rate<75 and madical_case=="y":
    print('You had a madical case')
    print('So you are allowed in the exam')
else:
    print("You aren't Allow in The exam")
