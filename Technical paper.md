
## Object-oriented programming system
Object oriented programming is a method used for designing a program using classes and objects.
             It simplifies software development by providing some concepts.those are

![enter image description here](https://static.javatpoint.com/images/java-oops.png)
             
 - Object
 - Class
 - Inheritance
 - Polymorphism
 - Abstraction
 - Encapsulation

## Object
An object can be defined as an instance of a class. an object contains an address
 and takes up some space in memory.object can be physical or logic.
 the implementation of class is Object.A class is not visible but object is visible.
 ## Class
 A class is defined as collection of objects which have similar properties. it is a logical entity.The primary purpose of class is to store data and information. The members of a class defines the behaviour of a class.A class is the blueprint of a object.
 A Class in java contains:
 

 - fields
 - methods
 - constructors
 - blocks
 - nested class and interface

 ## Create a class
 Syntax:
 public class {
 
            int x=10;
}            
## Create a object
Syntax:

	public class Main {

		  int x = 10;

		  public static void main(String[] args) {
		  
		            Main myObj = new Main();
		    
		            System.out.println(myObj.x);
		    
	  }
	}
You can also create a object of a class and access it in another class.This is often used for better organisation of classes.The name of the java file should be same as class name which contains the main method.
## Method 
a method is like a function which is used to expose the behaviour of an object.
## new key word
The new keyword is used to allocate memory at runtime.
## Constructor
A Constructor in java is a special method that is used to initialize objects.The constructor is called when an object of a class is created.
## inheritance
Inheritance is a mechanism in which one object acquires all the properties and behaviours of a parent object. By this inheritance we can create a new classes that are built upon existing classes.
**syntax:
 class Subclass-name extends Superclass-name
  {
  //methods and fields
  }**
  here a class which is inherited is called a parent or superclass, and the new class is called child or subclass.
  ## Polymorphism
  Polymorphism is the ability of data to be processed in more than one form.. It allows the performance of the same task in various ways.
  ## Method overloading
 if a class has multiple methods having same name but different in parameters is known as method overloading.
 **example:
   class Calc{
   void sum(int a,long b){
   System.out.println(a+b);
   }
  void sum(int a,int b,int c){
  System.out.println(a+b+c);
  }
  public static void main(String args[]){
  Calc obj=new Calc();**
}
## method overriding
if a subclass has he same method as declared in the parent class is known as method overriding. 
**Example:
class  Human{ 
  public  void eat()  {  
  System.out.println("Human is eating");  
 }
   }  
   class  Boy  extends  Human{  
     public  void eat(){ 
     System.out.println("Boy is eating"); 
    } 
     public  static  void main(  String args[])  { 
      Boy obj =  new  Boy(); 
        obj.eat(); 
        } 
  }**
  ## Abstraction
  Abstraction can be defined in simple way as the process of identifying only the required characteristics of an object ignoring the irrelevant details.
  we can also define this in simple words as
  **Abstraction**  is a process of hiding the implementation details and showing only functionality to the user.
  In java, abstraction is achieved by interfaces and [abstract classes.We can achieve 100% abstraction using interfaces.
  

## Abstract classes and methods

 -   An abstract class is a class that is declared with an  abstract keyword.
 -  An abstract method is a method that is declared without implementation.
 - it can have constructors and static methods also.
 
 ## Encapsulation
 Encapsulation in java is a process of wrapping code and data together into a single unit. it is a protective shield that prevents the data from being accessed by the code outside this shield.
 Encapsulation can be achieved by Declaring all the variables in the class as private and writing public methods to get and set the values of variables.
 ## Advantages of Encapsulation
 
 - Data hiding
 - increase flexibility
 - Re-usability
 - Testing code is simple
 
 ## References
 
 - www.javatpoint.com
 - www.geeksforgeeks.org
 - www.w3schools.com

 

