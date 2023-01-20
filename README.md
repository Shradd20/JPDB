# Title:- STUDENT ENROLLMENT FORM USING JDPB_L2Explore
Mini Project for Student Enrollment Form



"This project is all about basics of JsonPowerDB (JPDB) and how to use JPDB for CRUD operations."

#### About JsonPowerDB:
JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

#### Benefits of using JsonPowerDB
Simplest way to retrieve data in a JSON format.
Schema-free, Simple to use, Nimble and In-Memory database.
It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
It is low level (raw) form of data and is also human readable.
It helps developers in faster coding, in-turn reduces development cost.

#### Description:-

In this mini project we have Create a Student Enrollment Form which should should store data in the database.

There are three control buttons [Save], [Change] and [Reset] at the bottom of the form. On page load or any control button click, an empty form will be displayed and the cursor will remain at the first input field in the form which will have the primary key in the relation. All other fields and buttons should be disabled at this time.

User will enter data in the field having primary key and

If the primary key value does NOT exist in the database, enable [Save] and [Reset] buttons and move the cursor to the next field and allow the user to enter data in the form.

Check that the data should be valid i.e. no empty fields.

Complete the data entry form and click the [Save] button to store the data in the database and go to step-2.

If the primary key value is present in the database, display that data in the form. Enable [Change] and [Reset] buttons and move the cursor to the next' field in the form. Keep the primary key field disabled and allow users to change other form fields.

Check that the data should be valid i.e. no empty fields.

Click on [Change] button to update the data in the database and go to step-2.

Click [Reset] to reset the form as per the step-2.

#### Prerequistic:
 
 Install Netbeans on your desktop and add Talent API Tester Extension in chrome.
 
 #### Steps:
 
 1. Create a html form which has different fields Roll-No, Full-Name, Class, Birth-Date, Address, Enrollment-Date. (here Roll no is primary key)
 2. Create 3 buttons named Save, Change, Reset by javascript function name saveData(), changeData(), resetForm().
 3. On running this application, on webpage an empty form will be displayed and the cursor will remain at the roll no field in the form which is the primary key in the relation. All other fields and buttons are disabled at this time.
 4. User will enter data in the field having primary key and if the primary key value does NOT exist in the database,  [Save] and [Reset] buttons are enabled to allow the user to enter data in the form.
 5. Else if the primary key value is present in the database, display that data in the form. Enable [Change] and [Reset] buttons and allow users to change other form fields.

#### Output: 

![Screenshot (118)](https://user-images.githubusercontent.com/68496510/213685784-3320b84f-6229-4921-9a2d-8d4acf66c407.png)
![Screenshot (119)](https://user-images.githubusercontent.com/68496510/213685983-a2b695c0-59cb-40e9-a03b-7c5219fec969.png)
