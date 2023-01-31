class shape(square):
   
  # Constructor
  def __init__(self, name, colour):
    self.name = "square"
    self.colour = "colour"
 
  # To check if this person is an employee
  def Display(self):
    print(self.name, self.colour)
 
 
# Driver code
emp = shape("square", "red") # An Object of Person
emp.Display()