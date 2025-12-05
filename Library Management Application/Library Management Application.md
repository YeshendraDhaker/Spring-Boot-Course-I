###### **Problem Statement:**



Suppose you are working on a project, "ReadWell,” a console Library Application created using the concepts of IOC and DI using annotations.



There are two types of users Students and Admin. Admin can add books to the library, and students can issue available books.



Tasks:



1\. Go to start.spring.io and create a new project.



&nbsp;2. Add the necessary dependencies for the project.



&nbsp;3. Create a Book interface with the following methods:



&nbsp;a. getBookName()



&nbsp;b. setBookName()



&nbsp;c. isIssued()



&nbsp;d. issue()



&nbsp;4. Create MyBook class which implements the Book interface. Override the interface methods and add the following attributes:



&nbsp;a. String name



&nbsp;b. boolean isIssued(false by default)



&nbsp;5. Create a BookList interface with the following methods:



&nbsp;a. getAllBooks()



&nbsp;b. addBook()



&nbsp;6. Create the class MyBookList which implements the BookList interface. Override the interface methods and add the following attribute:



&nbsp;a. BookList(List of Books)



&nbsp;b. Add an init() method with @PostConstruct annotation and add some default books in the bookList through it.



&nbsp;7. Create a User interface with the following methods:



&nbsp;a. setDetails()



&nbsp;b. getAllBooks()



&nbsp;c. issueOrAddBooks()



&nbsp;8. Create Admin and Student classes which implement the user interface with similar attributes:



&nbsp;a. String name



&nbsp;b. BookList(interface)



&nbsp;c. Implement issueOrAddBook() methods according to the user type.



&nbsp;• If the user is Admin, he/she can add books



&nbsp;• If the user is a Student, he/she can issue books.



&nbsp;9. In the main application, get Context from SpringApplication. Run and create a console application with the flow shown in the flowchart.



&nbsp;10. Run and test your code.

