Student Marks Dictionary - Python Program

📝 Problem Statement
This Python program is designed to:

Create a dictionary where student names are used as keys and their marks as values.

Ask the user to input a student's name.

Retrieve and display the corresponding marks of that student.

If the name isn't found in the dictionary, show a friendly message saying the student doesn't exist.

🚀 How It Works
The program first creates a dictionary like:

python
Copy
Edit
student_marks = {"Alice": 95, "Bob": 88, "Charlie": 76, "David": 90}
Then it asks the user to enter a student's name.

It checks the dictionary for that name and prints:

✅ The marks if found.

❌ A message like "Student not found!" if the name doesn’t exist.




Task 2: List Slicing and Reversal - Python Program
📝 Problem Statement
This Python program is built to:

Create a list of numbers from 1 to 10.

Extract the first 5 elements using list slicing.

Reverse the sliced portion.

Print both the sliced and reversed lists.

🚀 How It Works
The list is created using:

python
Copy
Edit
numbers = list(range(1, 11))  # [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
The first 5 elements are sliced like this:

python
Copy
Edit
sliced = numbers[:5]  # [1, 2, 3, 4, 5]
The sliced list is then reversed:

python
Copy
Edit
reversed_sliced = sliced[::-1]  # [5, 4, 3, 2, 1]
📦 Output Example
python
Copy
Edit

Original List: [1, 2, 3, 4, 5, 6, 7, 8, 9, 10]
Sliced List (First 5 elements): [1, 2, 3, 4, 5]
Reversed Sliced List: [5, 4, 3, 2, 1]
