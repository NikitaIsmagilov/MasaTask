# MasaTask

(20%) 1. Enhance printSchool() method so it prints all of the information about the school in the following formats:
School data:
============
Name
Address
Phone

Classes
=======
Class 1: name
Teacher: firstName lastName professions as a comma delimited list
Students:
1: firstName lastName: age
...

Class 2 (in case exists and so on iterating over the sholw collection of classrooms in a school)
...

(5%) 2. Explain why History constant cannot be used in constants.ts

(5%) 3. Provide a solution for #2.

(5%) 4. Add fullName() method to helpers.ts that receives firstName and lastName;
	(2%) 4.1. Add fullName() method to Teacher and Student types that utilizes method added in #4.
	(2%) 4.2. Refactor the code of printSchool() to use the relevant type fullName() method instead of referencing properties of firstName and lastName.

(15%) 5. Fix the logic for getClassYoungestStudent().

6. #1 output should:
	(10%) 2.1. Be sorted ascending by a name of the class;
	(10%) 2.2. All students in a class should be sorted by lastName and then by firstName.
	
(25%) 7. Add a method that tranfers a student by name from one class to another:
	Prototype: services.transferStudent(fullName: string, fromClassroom: Classroom, toClassrom: Classroom): void
	Verify that the transfer is made correctly by calling to printSchool() before and after the transfer.

(40%) 8. Add a method to create a school dynamically:
	Number of classes;
	Generation of a teacher for each class;
	Random number of students in each class up to some limit (i.e. no more than 30 students in a class)
	Verify output by solution added in #1
	
9. NOT REQUIRED (+++ BONUS)
	Refactor the resulting solution using the knowledge larned during the latest session:
	- module
	- interfaces
	- classes
		- constructors
