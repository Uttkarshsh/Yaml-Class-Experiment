YAML Data Processing Experiment
This project demonstrates how to work with YAML files in Python, specifically focusing on processing student data. The application allows you to:
✅ Load student information from a YAML file.
✅ Display all students.
✅ Filter students based on their GPA.

Project Structure
Copy
Edit
.
├── README.md
├── requirements.txt
├── students.yaml
└── app.py
Components
1. students.yaml
Contains student data in YAML format. Each student entry includes:

name: Student's name

age: Student's age

major: Field of study

gpa: Student's Grade Point Average (GPA)

Example:

yaml
Copy
Edit
students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8

  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
2. app.py
The main Python script that processes the YAML data. It includes the following functions:

load_data(file_path): Loads and parses the YAML file.

display_students(students): Displays information about all students.

filter_students_by_gpa(students, min_gpa): Filters students based on a minimum GPA.

main(): Orchestrates the program flow.

3. requirements.txt
Lists the project dependencies:

ini
Copy
Edit
pyyaml==6.0.1
Setup and Installation
Clone or download this repository.

Install the required dependencies using:

bash
Copy
Edit
pip install -r requirements.txt
Usage
Run the application using:

bash
Copy
Edit
python app.py
The program will:
1️⃣ Display all students and their information.
2️⃣ Prompt you to enter a minimum GPA value.
3️⃣ Show students who meet or exceed the specified GPA threshold.

Example Output
yaml
Copy
Edit
All Students:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Bob, Age: 22, Major: Mathematics, GPA: 3.5
...

Enter minimum GPA to filter students: 3.7

Students with GPA >= 3.7:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
![image](https://github.com/user-attachments/assets/543318dc-619b-405f-bbb7-ea487ace5161)

Features
✅ YAML file parsing using PyYAML
✅ Student data management
✅ GPA-based filtering
✅ Clean and organized code structure
✅ Error handling for file operations

Technical Details
Uses yaml.safe_load() for secure YAML parsing.

Stores student data in a list of dictionaries.

Implements GPA filtering using list comprehension.

Handles floating-point GPA values.

Dependencies
Python 3.x

PyYAML 6.0.1

Notes
⚡ Ensure that app.py and students.yaml are in the same directory.
⚡ The program expects valid YAML syntax in the input file.
⚡ GPA values should be numeric (floating-point numbers).
