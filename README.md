# Python--creation

### 🧮 Python Data Structures & Conditional Logic – Practice Program

This project demonstrates Python fundamentals including:

Lists – creation, indexing, insertion, deletion, sorting

Dictionaries – key-value operations, updating, accessing

Sets – unique collections, union & intersection

Conditional statements – input-based decision making

🔹 Lists: Creation, Modification, and Access
age_list = [24, 25, 26, 27, 28]
name_list = ["Ali", "Sara", "John", "Meera", "Kiran"]

# Append
name_list.append("Yazhini")

# Insert
age_list.insert(2,30)

# Remove
name_list.remove("Yazhini")

# Pop
popped_age = age_list.pop()

# Extend
age_list.extend([30,29,26])

# Sort (descending)
age_list.sort(reverse=True)

# Max, Min, Sum
max_age = max(age_list)
min_age = min(age_list)
sum_ages = sum(age_list)

# Accessing list elements
print(name_list[0])
print(name_list[2:5])
print(name_list[-1])

🔹 Dictionary: Creation, Modification, and Access
student_marks = {
    "Ali": 85,
    "Sara": 78,
    "John": 92,
    "Meera": 66,
    "Kiran": 74
}

# Access value
print(student_marks['John'])

# Add student
student_marks['janani'] = 80

# Update student mark
student_marks["Meera"] =95

# Delete student
del student_marks["Kiran"]

print(student_marks.keys())
print(student_marks.values())
print(student_marks.items())

🔹 Sets: Creation & Operations
my_set = set(['a', 'e', 'i', 'o', 'u', 'a', 'a', 'i'])
print("my_set:", my_set)

# Attempt to modify set — results in error
try:
  my_set[4] = 's'
except TypeError as e:
  print("Error:", e)

set1 = {1, 3, 5, 7, 9}
set2 = {2, 3, 5, 8, 10}

union_set = set1.union(set2)
intersection_set = set1.intersection(set2)

🔹 Conditional Statements: Performance Evaluation
score = int(input("Enter your score (0 to 10): "))

if score > 10 or score < 0:
    print("Invalid input. Score must be between 0 and 10.")
elif score > 7:
    print("Above Average: Excellent work! Keep it up.")
elif score >= 4:
    print("Average: Good effort! Keep practicing, there's room for improvement.")
else:
    print("Below Average: Need to improve your performance. Consistent practice will lead to better results.")

✔️ What This Program Demonstrates
Topic	Concepts Practiced
Lists	indexing, slicing, insert, append, pop, remove, extend, sort
Dictionary	keys(), values(), items(), update, delete
Sets	uniqueness, union, intersection
Conditionals	nested IF-ELIF-ELSE, input validation

If you want, I can also:
✔ format this into a Jupyter Notebook
✔ add comments & expected output
✔ add screenshots
✔ add explanations for beginners
✔ rewrite in simpler or more technical language
