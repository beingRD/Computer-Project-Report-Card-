# Computer-Project Report Card Creator

Student Report Card System Project in C++ is a simple console application built without the use of graphics. 
This project student report card system help in managing the record of students according to their roll no. 

In this project I tried to enter all details of students like roll no, name, marks in all five subjects, etc. and tried to maintain all the possibility which may help the user to enter more record if he/she requires.

1. Create student report card record: This feature creates a new student record containing his marks. For this the information to be provided are the name and roll no. of the student, and the marks obtained by him/her in 5 subjects – Physics, Chemistry, Maths, English and Computer Science.
2. Read all students report card record: The void display_all() function in this student report card system project in C++ has been used for this feature. It basically shows the progress report of all the students added in file. This feature displays the roll no. and name of all the students, the marks obtained by them in 5 subjects – Physics, Chemistry, Maths, English and Computer Science, along with the percentage and grade of each student.
3. Read specific student’s report card record: This feature is same as the one explained above, except it shows the progress report and relevant data related to a particular student.
4. Display all students’ grade report: This feature enlists all the students’ record saved in file. The grade report is displayed in a tabular form with roll no. and name of the students, marks achieved in the five subjects, and the grade and percentage obtained by them.
5. Modify student’s report card record: In student report card system project in C++, this feature is used to edit the report card record of a particular student. For this, the name and roll no. of the student is sought. Upon successful modification, the program displays the message “Record Updated”. If no record of student is found in file, it displays the message “Record not found”.
6. Delete student record: This feature deletes the report card record of a particular student; it first of all asks for the name and roll no. of the student whose record is to be deleted.

# Header Files Used

iostream.h contains the following function: 

cin
Declaration: cin>>s;
cin is used to get a character or an integer(s) from the standard input stream.

cout
Declaration: cout<<s;
cout copies a character or a string or an integer(s) to the standard output stream.

conio.h contains the following function:

clrscr
Declaration: clrscr(void);
clrscr clears the current text window and places the cursor in the upper left hand corner.

getch
Declaration: getch(void);
getch reads a single character directly from the keyboard without echoing the screen.

stdio.h contains the following function:

remove
Declaration: remove(“file name”);
It is used to delete a file.

rename
Declaration: rename(“old name”, “new name”);
It is used to rename an existing file.

gets
Declaration: gets(char*s);
It collects a character string terminated by a new line from the standard input stream stdin.

fstream.h contains the following function:

read
Declaration: istream &read ((char*)&obj, sizeof(obj));
read function reads size of object from the associated stream and puts them in the buffer pointed by the object.

write
Declaration: ostream &write ((char*)&obj, sizeof(obj));
write function writes size of(obj) associated stream from the buffer pointed by the object.

Seekg
Declaration: istream &seekg (long);
seekg moves the get_pointer to a position related to the current position.

process.h contains the following function:

exit
Declaration: exit(int n);
exit takes an integer input an brings the control out of the program.

iomanip.h contains the following function:

setw
Declaration: setw(int);
The setw() function is used to set the field width of the output data.

Function Used

INTRO( ): to give introduction note to the user.
CALCULATE( ) : to calculate the percentage and grade of the student.
GETDATA( ) : to take information from user.
SHOWDATA( ): to display the information given by user.
SHOWTABULAR( ): to display information in tabular form.
WRITE_STUDENT( ): to write record in file.
DISPLAY_ALL( ): to display all records from file.
DISPLAY_SP(): to read specific record on file on the basis of roll number.
MODIFY_STUDENT( ): to modify a record.
DELETE_STUDENT( ): to delete a record from file.
CLASS_RESULT( ): to display all students grade report.
RESULT( ): to display result menu.
ENTRY_MENU( ): to display the menu of the features of the program.

