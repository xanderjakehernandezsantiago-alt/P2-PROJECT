def calculate_avrage(score1, score2, score3):
    return (score1 + score2 + score3) / 3

students = int(input("how many students? ")) 

for I in range (students) :
    print("\nStundent", I + 1) 

    name = input (" enter name : ") 
    activity1 = float(input("Activity1:" )) 
    activity2 = float(input("Activity2:" )) 
    activity3 = float(input("Activity3:" )) 

    average = calculate_average (activity1, activity2, activity3)

    if average >= 90:
       status = "Excellent"
    elif avrage >= 80:
       status = "Very Good"
    elif average >= 75:
       status = "Passed"
   else:
       status = "Failed"

   print("\nName:", name) 
   print("activity1:", activity1) 
   print("activity2:", activity2)
   print("activity3:", activity3)
   print("Avrage:", round(avrage, 2)) 
   print("status", status) 
   