# REQUIREMENTS
## Introduction
Digital Student info is a console-based project written in C that is built on the idea of keeping track of students' information. You may add, edit, and remove students from this page. There is also an option to see all students and their records, search students' records by roll number and course, amend their records, and track their attendance, as well as all of the functions listed below in this project. The main advantages of doing so are as follows: Eco-Friendly, Controlling student data effectively, Keep an eye on your students' progress. The system is both cost-effective and user-friendly. A single solution for all aspects of college administration Forums, attendance, timetable, marks, grades, and examination schedule are all easily accessible.
## Identifying Feature
  --Applications & Recruitment    :Student management system should allow strong connections to be built with prospects from lead to closed-won.
  
  --Resource Planner(Timetabling) :Provide a clear overview of timetables and scheduling for students, staff, and locations. Avoiding conflicts and assisting in forward planning.
  
  
  --Fees, Scholarship and Funding :Minimize delays in application processing by collecting and reporting appropriate eligibility criteria.
  
  --Student Management            :Facilitate student engagement with their peers and tutors. Allowing students to view personal details, schedules, academic results and more.
## Cost and Features
  - Time : Digital Student info changes over a period of time in terms of Availability, Scalability.
  - Cost : Our Digital Student info application reduces the human power and evolved in terms of features with minimal cost.
## Defining Our Requirements:
   1.	Student name
   2.	Roll no
   3.	Branch
   4.	Grade
   5.	Gender
   6.	Personal details (like DOB, address, phone no, parents name, email id etc.)
   7.	Fee details (like total fee amounts, fee paid, fee remaining, due date, receipts)
   8.	Library details (like no of books taken and return, details of the book etc.)
   9.	Attendance details (like count of present and absent)
  10.	Hobbies
  11.	Extra curriculum activities
  12.	Remarks

## SWOT Analysis
![swot](https://user-images.githubusercontent.com/94296103/146381723-ba9bac24-3c4c-43ea-876d-0cc4e815c746.jpg)

### Strength
- Students can use this to view and manage their details.
- By seeing their marks they will get updated about their details.
### Weakness
- Not more than one student can be viewed or update his/her details.
### Oppurtunities
- Students who need to see and update their details this will be very helpfull.
### Threats
- During the holidays no one will be using this project.

## 4W's and 1'H
### Who:
This project is helpful for managing student information by adding, updating, removing, viewing and searching for details.
### What:
Students can use this to peer and manage their details.
### When:
If a student wants to know the details and update them according to their needs.
### Where:
Student needs to be updated about his attendance and all the college details this project can be really use full.
### How:
Student will be knowing his or her details and view and can If anything goes wrong the person might be able to change the details quickly.

## Detail requirements
### High Level Requirements:

|ID|Concept|Description|status|
|--|-------|-----------|------|
|H_1|Students Profile|The full information of each and every student must bemaintained in System along with the facility to regularly update it from timeto time at regular intervals which will be easily possible through eachstudents unique id.|Completed|
|H_2|Attendance|This module is meant to keep detailed record of the studentsthroughout the session. It includes attendance of students in regular classes,lectures, seminars, practicals, clinical work.|Completed|
|H_3|Record of Examination Results|This phase will maintain information ofstudents performance track record. All the result of student includinginternal class test, unit test, mid semester marks, sessional marks ,practicalexams and final examination record will be kept.|TBD|
|H_4|Providing examination reports|It is meant to analyse each student performance on the individual level as well as among the group.|TBD|

### Low Level Requirements: 
| ID | Description | Category | Status | 
| ----- | ----- | ------- | ---------|
| L_1 | It describes the class diagrams with the methods and relations between classes and program spec. It describes the modules so that the programmer can directly code the program from the document.Modules like UML diagram,Sequence Diagram,Class Diagram,Entity Diagram etc...  | Techincal | TBD-S1 | 
| L_2 | It describes how stuent Management Systems provide capabilities for entering student test and other assessment scores, build student schedules, and manage many other student-related data needs in a school and colleges. | Techincal | TBD-S1 |
| L_3 | It this Student Management System project it shows how the modules is implemented and assign to each module. | Techincal | TBD-S1 |  
| L_4 | In this Student Management System project, user can create, display, search, modify and delete student record from a file and this all data is represented by Low level Design Through diagrams. | Techincal | TBD-S1 |

## Folder Structure
Folder        | description
--------------| ----------------------------------------------
`inc`         | All header files
`src`         | Main source code for calendar
`test_files`  | All source code and data for testing purposes
`unity`       | Unity test cases
`build`       | Build output (Not included in git)
`main.c`      | Main program file

# Test Plan
## Table:High level Test Plan
****

|Test ID	| Description |	Exp I/P	| Exp O/P	| Actual Out | Type Of Test|
|-------|-------------|---------|---------|------------|-------------|
|H_01| If User enters correct password and username - Checking the password and username |	Data| Success - Program continues |	Success - Program continues |	Scenario based|
|H_02|If User enters wrong password and username - Checking the password and username |	Data | Fails - Program exit |	Fails - Program exit| Scenario based|

## Table:Low Level Test Plan
|Test ID|H ID|Description	|Exp IN	|Exp OUT|Actual Out|Type Of Test|
|-------|----|------------|-------|-------|----------|------------|
|L_01 | H_01 | Add new student Details|Data|	Add student |	Add student|Requirement based|
|L_03 | H-01 | Search student details by ID	|Data| Searches student deatils |	Searches student deatils |	Requirement based|
|L_03 | H-01 | Search student details by Course	|Data| Search student deatils|	Searches student deatils |	Requirement based|
|L_04 |	H_01 | View all students list|Data| List of student details| List of student details	| Requirement based|
|L_05	| H_01 | Updating login password	| Data |	Change of paassword	| change of password |	Requirement based
|L_02	| H_01 |Delete student details by ID |	Data |	Delete's student detail |	Delete's student detail	| Requirement based
|L_06	| H_01 | User wants to exit?	| Data	| Exit	| Exit	| Requirement based

## Output
### VIDEO https://user-images.githubusercontent.com/94296103/146318530-342f55c4-b3bd-4163-b91f-28e8a2fabbc6.mp4

### Main Page
![pic1](https://user-images.githubusercontent.com/95902506/146221390-96451cca-1081-4a9e-ba53-d92b1ae068f4.jpg)

### Login Page
![WhatsApp Image 2021-12-15 at 5 34 19 PM](https://user-images.githubusercontent.com/46160797/146189212-80f92f96-f41d-4013-82e9-edaa52c12487.jpeg)

### Main Menu Page
![WhatsApp Image 2021-12-15 at 5 34 19 PM](https://user-images.githubusercontent.com/55519209/146189618-eff1dffb-5a35-4ad6-bd5c-f3c9496a7e68.jpeg)
