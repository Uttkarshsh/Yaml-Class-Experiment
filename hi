YAML Data Processing Experiment

This project demonstrates how to work with YAML files in Python, specifically focusing on processing student data. The application allows you to load student information from a YAML file, display all students, and filter them based on their GPA.

Project Structure

.
├── README.md
├── requirements.txt
├── students.yaml
└── app.py

Components

1. students.yaml

Contains the student data in YAML format. Each student entry includes:

name: Student's name

age: Student's age

major: Field of study

gpa: Grade Point Average

Example:

students:
  - name: Alice
    age: 21
    major: Computer Science
    gpa: 3.8
  - name: Bob
    age: 22
    major: Mathematics
    gpa: 3.5
  - name: Charlie
    age: 20
    major: Physics
    gpa: 3.9
  - name: David
    age: 23
    major: Chemistry
    gpa: 3.2
  - name: Eva
    age: 21
    major: Computer Science
    gpa: 3.7

2. app.py

The main Python script that processes the YAML data. It includes several functions:

load_data(file_path): Loads and parses the YAML file.

display_students(students): Displays information about all students.

filter_students_by_gpa(students, min_gpa): Filters students based on minimum GPA.

main(): Orchestrates the program flow.

3. requirements.txt

Lists the project dependencies:

pyyaml==6.0.1

Setup and Installation

Clone or download this repository:

git clone <repository_url>
cd <repository_name>

Install the required dependencies:

pip install -r requirements.txt

Usage

Run the application:

python app.py

The program will:

Display all students and their information.

Prompt you to enter a minimum GPA value.

Show students who meet or exceed the specified GPA threshold.

Example Output

All Students:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Bob, Age: 22, Major: Mathematics, GPA: 3.5
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: David, Age: 23, Major: Chemistry, GPA: 3.2
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7

Enter minimum GPA to filter students: 3.6

Students with GPA >= 3.6:
Name: Alice, Age: 21, Major: Computer Science, GPA: 3.8
Name: Charlie, Age: 20, Major: Physics, GPA: 3.9
Name: Eva, Age: 21, Major: Computer Science, GPA: 3.7

![image](https://github.com/user-attachments/assets/a7ed7eea-4f58-4bfb-9d37-19040bd67310)


Features

YAML file parsing using PyYAML.

Student data management.

GPA-based filtering.

Clean and organized code structure.

Error handling for file operations.

Technical Details

Uses yaml.safe_load() for secure YAML parsing.

Student data is stored in a list of dictionaries.

GPA filtering is implemented using list comprehension.

Handles floating-point GPA values.

Notes

Ensure app.py and students.yaml are in the same directory.

The program expects valid YAML syntax in the input file.

GPA values should be numeric (floating-point numbers).

License

This project is open-source and available under the MIT License.

Happy Coding! 🚀

