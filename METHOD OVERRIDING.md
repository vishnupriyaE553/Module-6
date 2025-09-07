# Exp.No:26  
## Method Overriding

### AIM  
To write a Python program to demonstrate polymorphism by creating two classes India and USA with the same method names (capital(), language(), and type()) and then accessing them using a common interface.

### ALGORITHM

1. Start the program.
2. Define the class India with methods capital(), language(), and type().
3. Define the class USA with the same methods capital(), language(), and type().
4. Create objects obj_ind for the India class and obj_usa for the USA class.
5. Use a for loop to iterate through the objects and call the common methods.
6. Display the output for both countries.
7. End the program.

### PROGRAM
```
Reg.No: 212223060305
Name: Vishnu priya E

class India():
	def capital(self):
		print("New Delhi is the capital of India.")
	def language(self):
		print("Hindi is the most widely spoken language of India.")
	def type(self):
		print("India is a developing country.")
class USA():
	def capital(self):
		print("Washington, D.C. is the capital of USA.")
	def language(self):
		print("English is the primary language of USA.")
	def type(self):
		print("USA is a developed country.")
obj_ind = India()
obj_usa = USA()
for country in (obj_ind, obj_usa):
    country.capital()
    country.language()
    country.type()
```
### OUTPUT

<img width="1058" height="276" alt="image" src="https://github.com/user-attachments/assets/5e118b02-a6b0-4ffc-ae78-1e87d5bf2aef" />

### RESULT
Thus, the program to demonstrate polymorphism using two classes was executed successfully and the output was verified.
