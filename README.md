class Student:
   #constructor
    def __init__(self,name,age,year,country):
       
       #name, age, year and country is an attribute or properties
       self.name = name
       self. age = age
       self.year = year
       self.country = country
       
    #methods -functions according to what we want
    def show_details(self):
        print("showing Details: ")
        print(self.name)
        print(self.age)   
        print(self.country)
        print(self.year)
        
    #method to change details
    def change_details(self):
        print("please Enter your age: ")
        self.age = int(input())
        print(f"The updated age is {self.age}")
    
    #methods are always created in class

#object - an instance of class
Matt = Student("Matt" , 13, "1st year", "Ireland")
Matt.show_details()
Matt.change_details()
Matt.show_details()
