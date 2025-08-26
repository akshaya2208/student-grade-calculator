# student_grade_calculator.py

print("=== Student Grade Calculator ===")

# Input marks for three subjects
marks1 = float(input("Enter marks for Subject 1: "))
marks2 = float(input("Enter marks for Subject 2: "))
marks3 = float(input("Enter marks for Subject 3: "))

# Calculate total and average
total = marks1 + marks2 + marks3
average = total / 3

# Determine grade
if average >= 90:
    grade = "A"
elif average >= 80:
    grade = "B"
elif average >= 70:
    grade = "C"
elif average >= 60:
    grade = "D"
else:
    grade = "F"

# Display results
print("\n--- Results ---")
print("Total Marks =", total)
print("Average =", round(average, 2))
print("Grade =", grade)
