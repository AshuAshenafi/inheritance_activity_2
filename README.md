##Inheritance activity
 _________________________________________________________________________________________________________________
Using the previous "Inheritance completion activity #1 and #2", 
Product class which is parent for book and software classes 
is made abstract, so that instance of Parent object can not be created.

* Different products (Books and Softwares) are hardcoded with all their attributes except one book's code so
the user is prompted to enter book code.
* The entered code is assigned to the book and displayed in the console.

* This exercise overrides .equals() method in all the Product, Book and Software class so that two different objects 
are compared at attribute level. for example book1.equals(book2) compares if the author and description attributes of 
both the books are identical. 

* The application also checks if either of the book objects are null, or if they belong to
different class (getClass()) that makes the comparison result automatically false.
and shows the result of comparison in boolean form. 