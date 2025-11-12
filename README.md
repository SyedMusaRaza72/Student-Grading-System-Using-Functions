📘 Student Grading System Using Functions (Python)

✅ Project Description

This is a simple Python program that takes a student's percentage (or marks), processes it using a function, and returns the corresponding grade based on predefined conditions.
The program demonstrates the use of:

Functions

Conditional statements (if-elif-else)

User input

Returning values from functions



---

🧠 How It Works

1. User enters their percentage.


2. The percentage is passed to the function calculate_grade().


3. The function checks percentage range and returns a grade.


4. The program prints the result.




---

📌 Grading Criteria

Percentage Range	Grade

90% and above	A+
80% – 89%	A
70% – 79%	B+
60% – 69%	B
50% – 59%	C
Below 50%	Fail



---

🧾 Code Used

# Student Grading System Using Function

def calculate_grade(percentage):
    if percentage >= 90:
        return "A+"
    elif percentage >= 80:
        return "A"
    elif percentage >= 70:
        return "B+"
    elif percentage >= 60:
        return "B"
    elif percentage >= 50:
        return "C"
    else:
        return "(Fail)"

# Getting input from User
percentage = float(input("Enter your percentage: "))

grade = calculate_grade(percentage)
print("Your grade is:", grade)


---

▶️ How to Run

1. Open any Python IDE (VS Code, PyCharm, or Programiz online compiler).


2. Copy the code into a Python file (main.py or grading.py).


3. Run the program.


4. Enter the percentage when asked.




---

💡 Example Output

Enter your percentage: 84
Your grade is: A


---

🔚 End

Feel free to improve and extend this program by:

Taking marks of multiple subjects

Calculating total and percentage automatically

Saving student results in a file

