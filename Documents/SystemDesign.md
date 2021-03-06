## Team Members
1. Sabri Said
2. Yang Yizhou
3. Deji Adeyemo
4. Imad
5. Om Parkash
6. Silabela Mxolisi

## Introduction

A high-level summary, which all members in the group should understand and decide,
if it's helpful for them to read other documents.
The necessity of the project, what to do with evaluating the project itself, the description of the problem and how all these
make the team work together with a strategy

## Purpose and Goals

This application should be made because nowadays so many don't like to book their flight ticket offline where usually its crowded and it takes a lot of time and effort,
which is a kind of a traditional way to deal with customers,
so for that we need this application that will make it easier and with less effort. goal is to make the life of both customer and servant easier with an application which is easy to use and easy to train employees with. Our hopes is to streamline the checkout process with this software which can help out our employees.

## Proposed Scope\Architecture

  #### Architecture:

        The system will be developed in java. Using classes, having methods that can implement the CRUD methods,for example cancel a ticket.
        The database connection is a must for this project to keeo track of all the information entered by the user(Mysql xampp could be a good thing for this project) 
        Have a user interface which will contain the general information, username, id password etc, and have two implementations of the interface which will be admin and user, by this way we can control the permissions each user has. the design will include buttons and text boxes to insert texts and numbers and forms as well.

#### Design:
        Image background on the screen as well as buttons with different colors. buttons for like, login,logout,back,proceed..etc . A form for the user to show the flight ticket information or details and another form for the admin to keep track of the users. we also require a sign up and login form which will follow the same design patterns as the previously afore mentioned forms. 

##### Functionality:
        First page will have a well designed regestration system page. After which the user will be redirected to their supposed forms, I.e the admin will be directied to the users management form and the user will be taken to the booking flight form where they can fill up the information required.

## Project plan

Contributors.                Roles.                        

1.Sabri Said       > Original idea, Project manager, Documentation, programmer
3.Om Parkash        > programmer, Documentation
4.Yang Yizhou       > programmer, Documentation

## Business process model

the project will show the ticket information of locations inputed by user, and there is 
a book/pay user can click if the user is interested in a specific ticket,then the project would show the details of ticket and payment
if the user input wrong loaction name ,the app will give error message
we will find the best solution of how to design the user interface
and we have the idea ,then we do documentation,later we will try to implement the project using our tecknology
so far we already have a script ,hopefully we can have presentation soner or later,
all of our team is supposed to have some contribution of it

## Implementation plan

for this project we used java to build the basic structure ,and use mysql
to solve the database problem,and for the user interface ,we would like to use java as well,
for implement the database system,we still need other technology ,such as visual stusio code
and our team will try to find good technology to solve our problem

## Requirement 

The application has to achieve following goals;

-Simple  intuitive interface .
-Ability to achieve users requirements.
-input the data of user . 
-output the ticekt for user.
-Security of giving  the real data and keep the data.
-User Registration, This  describes the scenario where the user registers with the
Application by providing all the necessary details, in order to make reservations or
Bookings for flights
-User Login, This describes the scenario where the user logs into the
 application, with the username and password.
-Book Flight , This describes the scenario where user books airline ticket.



## Functional plan

As the application provides to register an account  and sign in to keep the Data of user in database,
and also admin login so admin can also have an account  to check the data and also change if need to.


## Testing plan

Test strategy is that,we should test every function one by one ,including system testing
the tester should have the ability to understand user point of view,then we should test the whole
program, the goal is that what basic thing user want from our App, is firstly information about flight , so we test flight details first and then we upload it and also , and we test database so that user can easly sign up and then can sign in without any trouble, for testing the booking system we give wrong information if it gives us ticekt so we need to fix it . 

## Milestones
   
  - Start Date: March 12, 2021
  - Milestone 3 Get a working regestration system interface(design part)
  - End Date: Be able to click on login,sign up,login as admin button and and it takes you to the new form : March 12, 2021

  - Start Date: March 13, 2021
  - Milestone 1 Get a working sign up interface(design part)
  - End Date: Be able to sign up :March 13, 2021
  
  - Start Date: March 14, 2021
  - Milestone 2 Get a working login(front in)  
  - End Date: Be able to login: March 14, 2021
  
  - Start Date: March 19, 2021
  - Milestone 5  sign up users(database connection,back in )
  - End Date: Be able to sign the user up and store the information in the database: March 19, 2021
  
  - Start Date: March 20, 2021
  - Milestone 6  sign in form(database connection,back in )
  - End Date: Be able to get the data of the users from db and sign them in if there is no error: March 20, 2021
   
  - Start Date: March 21, 2021
  - Milestone 7 booking interface(front in)
  - End Date: Be able to access and see the booking form: March 21, 2021
   
  - Start Date: March 26, 2021
  - Milestone 8 booking form(back in,java code,db connection)
  - End Date: Be able to book a flight ticket: March 26, 2021

  - Start Date: March 27, 2021
  - Milestone 8 GET the passenger details and payment one
  - End Date: Be able to see the flight ticket that is booked: March 27, 2021



  ## Existing Solution
In addition to describing the current implementation, you should also walk through a high level example flow to illustrate how users interact with this system and/or how data flow through it.

An user story is a great way to frame this. Keep in mind that your system might have different types of users with different use cases.


## Proposed Solution
Some people call this the Technical Architecture section. Again, try to walk through a user story to concretize this. Feel free to include many sub-sections and diagrams.

Provide a big picture first, then fill in lots of details. Aim for a world where you can write this, then take a vacation on some deserted island, and another engineer on the team can just read it and implement the solution as you described.


## Alternative Solutions
What else did you consider when coming up with the solution above? What are the pros and cons of the alternatives? Have you considered buying a 3rd-party solution ' or using an open source one ' that solves this problem as opposed to building your own?

## Maintenance plan

The resevation system has to evaluated regularly in order to assess whetherthe existing one is still useful or a new reservation system will be needed, by this we remove the existing errors as well as the enhancement of the currently used reservation system. Thus, it is an important stage since it greatly affects the cost that has to be incurred by the Airline Ticket Reservation System  whether modification can still be done or  entirely new reservation system is required.

## Open Questions
 Any open issues that you aren't sure about, contentious decisions that you'd like readers to weigh in on, suggested future work, and so on. A tongue-in-cheek name for this section is the 'known unknowns'.

## Reference Material
Throughout the process of system design we used amny reasources and references to make a very encompassing and successful system design document. we used :

https://www.its.dot.gov/research_archives/msaa/pdf/MSAA_SystemDesignFINAL.pdf System design template

https://www.cs.fsu.edu/~lacher/courses/COP3331/sdd.html as an example of how a system design document is written

https://www.freecodecamp.org/news/how-to-write-a-good-software-design-document-66fcf019569c/

## Summary
For the success of this system we will rely mostly on peer programming to minimise the errors that programmers may have. Our main focus will be on creating a user-friendly system that does not discriminate against gender, race, age, ethnic group and so on so our design will be highly maintained by allowing users to send emails should they wish to make comments or complaints about the design.
