# Assignment6_Cypress
Task 1- Create course using cypress with data from fixture

Precondition – Create json file “CourseData.json” and store all test data which is needed for below test.

Create custom command login which will accept username and password then perform login functionality. 
Note- Do not duplicate the code
Mouse Hover on Manage
Click on Manage Course
Click on Add New Course
Do not fill any values and click on Save
Verify error message “Please select a thumbnail!”

Upload any file from fixture folder
Enter course name, description
Type your name as INSTRUCTOR 
Note- use delay as argument to type slow use delay of 1000 ms
Set price 200
Select start date and end date
Click on category as Testing
Click on Save
Verify course added in the list
Select the same course and click on delete
Verify course deleted from the list
