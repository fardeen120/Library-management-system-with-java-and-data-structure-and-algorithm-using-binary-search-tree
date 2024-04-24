The major goal of this project is to develop a library management system that will allow students to check out books and administrators or librarians to add, edit, or remove entries in the library's catalogue. Thus, the system is divided into two sections: the admin's perspective and the user's perspective. 
To manage the accounts where the username and password are already specified, the administrator must first log in. 
Upon successfully logging in, he has the ability to add, remove, and update books. Any new book may be added by him to the current list of books. 
He has the same ability to remove any book that already exists. The administrator can change both the book's name and quantity under the update option. 
A binary search tree with nodes that have the book names sorted in order will be formed as soon as the admin adds more books. 
A student must now authenticate into the system with a valid university ID in order to issue or return any books. 
Only if the student's ID matches the list of student IDs from the institution will they be permitted to issue or return. 
The book that the student wants to be supplied will be found using its name in the binary search tree that has already been established.
A message stating that the book is not available in the library will print if it cannot be located in the tree. 
Additionally, the statement "This book is currently unavailable" will print if the book is out of stock. Please give it another go a few days later. 
Additionally, the student is only permitted to issue two books at a time. The librarian notes the time and date when a book is issued to a pupil. 
Additionally, the student is responsible for paying that specific fee if he fails to return the book by the deadline.
