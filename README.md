# Python-Assignment-2026
#SESAME DITHUPA
This repository holds a README.md file for the python Grading System Assignment which describes the contents and logic of each section in the project 

GRADEBOOK GRADING SYSTEM
Project Overview
This is a python project, a grading system developed to collect, manage and record student marks across multiple subjects.

SECTION A 
A basic gradebook system whereby the program:

1. Asks a user how many students there are and the program will keep on asking till the count is greater than 0 and is a whole number else it will print an error  
2. The user then provides a name and grade for each student. The program will repeat that step till the count of students is satisfied. 
3. Empty lists are created for names and grades that are collected during the program.
4. Every grade enetered should satisfy the validation of being between 0 and 100 else an error will be printed out. 
5. The names and grades collected for each student are then stored in the empty lists.a
6. After all student details for each student are collected and recorded the program then calculates the total and average of the class.
7. Then it will display the names, grades of students along with totals and class average.

SECTION B
In this section the system is expanded to handle 5 subjects' grades for each student.

1. The subjects being English,Math,Statistics,Geography and Commerce.
2. The subjects are stored in one list named subjects.
3. Program will then ask the user how many students there are and the program will keep on asking till the count is greater than 0 and is a whole number else it will print an error  
4. It will then ask for the students details being the name and grades for each subject by iterating through the subjects.
5. A list named student is created to store each student's name and grade and store the record as a tuple.
6.  Every grade entered should satisfy the validation of being between 0 and 100 else an error will be printed out. 
7. The student details are then stored in the student list.
8. Average grade for each student is then calculated.
9. Highest and lowest grades for each subject are also calculated.
10. The final output is each students name, their subject grades and averages along with the highest and lowest marks for each subject.

SECTION C
In this section the use of lists and tuples is replaced with the use of dictionaries.

1.  The subjects are stored in one list named subjects which are English,Math,Statistics,Geography and Commerce.
2. An empty dictionary named gradebook is create dto store the students names as a key along with her subjects and grades as values.
3. The second empty dictionart named subject_grades stores subject names as keys and await grades for each sunject as values.
4. Function to add a student,to get their name but the program will stop if the student already exists in the gradebook
5. An empty dictionary named grades then loops through each subject for every student once to collect thir grades.
6. Every grade entered should satisfy the validation of being between 0 and 100 else an error will be printed out.
7. Then stores the student into gradebook and grades into subject_grades dictionaries.
8. Function to update student grades it will ask for the student's name, if the name does not exist in the gradebook, it will stop else it will print out the subjects and ask which subject grade you want to update.
9. Every new grade entered should satisfy the validation of being between 0 and 100 else an error will be printed out.
10. The old grades are then replaced with new ones, and the gradebook dictionary is updated.
11. Function to remove student it will ask for the student's name, if the name does not exist in the gradebook, it will stop else it will remove all the students grades from the subjects before deleting the record.
12. Function to search student it will ask for the student's name, if the name does not exist in the gradebook, it will stop else it will calculate the students average and display all the subject grades and average.
13. Function to view all subject grades it would stop if subject entered is invalid or if gradebook is empty else will display each student's grade for the chosen subject.
14. Function to display all students and their marks stops if gradebook is empty else prints out student names,their grades per subject and personal average will then print the maximun and minimum grdaes for each subject.
15. A main menu Gradebook interface is what the users interact with to choose what specific function duty they want to perform .
Setup Instructions
1. Make sure Python is installed on your machine
2. Open the .py file for the relevant section in PyCharm or any Python editor
3. Run the file 



