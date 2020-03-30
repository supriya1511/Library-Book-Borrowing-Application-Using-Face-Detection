Despite the increasing availability of digital books, many still favor reading physical books and here comes the concept of borrowing a book from the library. Traditional system requires registration of borrowed books to the librarian and he has to enter the details into his system manually. But in case if the librarian is not available then the user has to wait for the arrival.  We are developing an automated library management system using face recognition. The system helps to reduce manual work for the library. The person who needs a book from the library has to go for the manual process of borrowing the book or returning the book. Through this application book is issued to the end user. Face recognition technology has widely attracted attention due to its enormous application value and market potential, such as real-time video surveillance system. In our system we are using dlib face recognition which is 99.38% accurate. This face recognition model helps to identify registered users.  To issue the book, firstly the barcode is scanned to identify the book and to issue the book to the user. Both the book issue and return events get stored in the database.  Following is the system’s approach:
1. Registering the user : Get the details of an user and Capture the image through webcam and extracting face encoding using dlib face recognition model to store it in a database for further identification purposes.
2. Identifying the person: Recognize the user's face by comparing encoding of faces stored in users database.
3. Search book : Searching if a book is available and if book is not available then students who have that book already will get notification of requirement. 
4. Book barcode scan: User holding book in front of camera it scan for a barcode and match barcode pattern in book database. Registering the book to the user and store the event in book borrow database.
5. Book issue or return : Face recognition model identifies the user in front of webcam and barcode of book get scanned. Then book get registered to identified user or if he/she want return then database is updated accordingly.
