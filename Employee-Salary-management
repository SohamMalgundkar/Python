 class employee():
  empcount=0
  incmt=1.10
  def __init__ (self,first,last,salary):
    self.first=first
    self.last=last
    self.salary=salary
    self.email=first.lower()+"."+last.lower()+"@questech.com"
    employee.empcou
  def fullname(self):
    return f"{self.first.title()} {self.last.title()}"
  def increment (self):
    self.salary=int(self.salary*employee.incmt)



class developer(employee):
  def __init__ (self,first,last,salary,prog_lang):
    super().__init__(first,last,salary)
    self.prog_lang=prog_lang


class manager(employee):
  def __init__(self,first,last,salary,Employee=None):
    super().__init__(first,last,salary)

    if (Employee is None):
      self.Employee=[]
    else:
      self.Employee=Employee
  def addemp(self,emp):
    if emp not in self.Employee:
      self.Employee.append(emp)
  def removemp(self,emp):
    if emp in self.Employee:
      self.Employee.remove(emp)
  def print_emp(self):
    for emp in self.Employee:
      print("-->",emp.fullname())
