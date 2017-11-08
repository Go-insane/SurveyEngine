# SurveyEngine

It is a project created upon industrial working standards and proceedures working under Aricent and Nasscom and we named it SARVEKSHAN
-----------------------

This project is to create a survey engine using Java where A user can conduct a survey where he/she can create a new survey and get it filled by other application users . 
It is a full fleshed java application project  with 2 modules user and admin.

-------What Project Does--------- 

It got 2 models user and admin

Only one admin is there. 
while there can be multiple users

User and admin have to login first

New user will first signup 
and then login to 
move inside application
There a user can either fill an ongoing survey request or create its own new survey.
We have impplemented a functionality of virtual currency.
Virtual currency is used here to provide survey filling reward which can be then used to create a new survey

Filling a survey will reward you an amount.
Conducting a survey will charge you amount.

The amount of reward and charge will depend on the number of questions and other factors. One user can fill one survey only one time.

In a new survey , four different type of questions can be created.

1.MCQs

2.Textboxes

3.Checklist

4.Answer type


Also for a new survey its cost on the basis of its configurations will be charged . Configurations can be set while creation .
Also after its creation , user can see that survey information like its status, asnwers, end date, amount, and survey results.
--------
In  Admin Module..
After each survey creation..its request is been passed to admin first which decides weather to pass it or not
admin manualy fills the survey and checks for abrupt words and questions etc 

Admin can also see any survey results and its information 

Admin also got privilages to end a survey any time

Admin is the caretaker of SurveyEngine 

It is a full fledged project that is been done in the proper industrial manneer as it should be done in a company
Proper packages and methodoly is used .Testing is also a part of it 
------------------



-----Requirements----
1.Oracle 10g or above installed in the system


2.Need any java ide and pull the project

If you are not able to pull it or showing some wierd errors then follow these steps:-
a)This must be classpath issue ....so manualy create a new java project

b)create all the packages under src in your project manualy   with exact same name like packeges in my src folder
--this will remove any class path problem because now you have created each package manually 

c) Now go to project directory or location in your system then in src--copy all files of each package individually from my packages in src folder to yours( do not copy package folder , instead go inside the package and copy the containing files in  yours) 


3. Create the required database tables in oracle that you will require in this project
I have provided pics of the description of the tables....
There are 4 tables 
Create them as it us.
Simple create commands are required to create these tables



4 . Now you are ready to Go!!!
Just change the username password to your own Oracle database
Go to the DBConn package which includes the only connection point to the complete project and replace 'username' and 'password' with you own


5. I have provided all the required jars also
Include all the jars to your project classpath before running it
(Google it ...how to add jars in a project in your your ide)



Woahhhh!!! It's done.....Now you are ready to run this project
--------------------------------------------------------------

Please dont forget to star rate it and also please contribute to the repo and provide updates







