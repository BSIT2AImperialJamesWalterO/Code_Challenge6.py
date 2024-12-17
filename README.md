# Code_Challenge6.py
print("Hi, Welcome to the Final Grade Calculator Program")

name = input("Please enter your name: ")

prelim = float(input("Enter your Prelim score: "))
midterm = float(input("Enter your Midterm score: "))
semi_final = float(input("Enter your Semi-Final score: "))
finals = float(input("Enter your Final score: "))
quiz = float(input("Enter your Quiz score: "))
project = float(input("Enter your Project score: "))

final_grade = (prelim * 0.15) + (midterm * 0.15) + (semi_final * 0.15) + (finals * 0.15) + (quiz * 0.15) + (project * 0.15)

print(f"Hi {name}, your final grade is: {final_grade:.2f}")

if final_grade >= 75:
    print("Congratulations! You passed the subject or course.")
else:
    print("Sorry, you failed the subject or course.")

print("Thank you for using this system")
