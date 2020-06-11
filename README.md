# python-variables

# Assigning values to variables
#An integer assignment
  Books = 60
#Floating point assignment
  Basic_Salary = 56342.65
#A string
  school = 'Zetech'
#printing the results
print(Books)
print(Basic_Salary)
print(school)

#In python you can assign the same value to  multiple variables
  x = y = z = 17
  print(x)
  print(y)
  print(z) #returns the same value i.e 17
  
#Assigning different values to multiple variables
  x, y, z = "Kevin", 101, 38.7
  print(x) #returns 'Kevin', a string
  print(y) #returns 101, an integer
  print(z) #returns 38.7, float
  
# Working with a '+' operator
  a = 5
  b = 10
  print(a+b) #the operator adds the value of a to the value b giving 15 as the answer.
  
  a = "Zetech"
  b = "University"
  print(a+b)  '''THe print result is Zetech University. this indicates that the reults of a '+' operator depends on the type of the assigned value.'''
# Creating objects
  class person:
    def _init_(self, name, age):
      self.name = name
      self.age = age
  student1 = person("Bravin", 19)
  print(student1.name)
  print(student1.age)

# Global variables
#A function using global variables
  def f():
    print(x)
  x = "I love school"
  f()
