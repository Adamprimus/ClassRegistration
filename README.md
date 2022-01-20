# ClassRegistration
Final Project CISC359
# ClassRegistrationDjango
Final Project CISC359 Fall 2021


Different parts of the project and the assigned person:

Created by Mame Gueye

Different tasks to discuss/complete


Database/Model requirements:

Student: StudentID(PK), FirstName, LastName, DateOfBirth, Major, ListOfCompletedClasses)
Transcript: EntryID(PK, hidden), StudentID(Foreign Key), Grade  
Major: MajorID(PK), MajorRequiredClasses  
Class: ClassID(PK), ClassSubject, ClassPrereqs, ClassCredits  

Start page has two forms. Login on the left half, and sign up on the right.

Sign Up Form
    -- Needs Name(text entry), major(from list), Date of Birth(from calendar)  
    -- Add time of sign-up to model  
    -- Check if email already used
Login form

Student landing page      
    -- Show registered classes if already registered  
    -- Show registering screen if not registered  

Register page   
    -- Show all classes  
    -- Option to filter classes  
    -- "shopping cart" system for classes, check out to register selected classes  
    -- Make sure prereqs are completed before registering  



Transcript Page?

    
URLs:
/ redirects to /login: login screen
/login redirects to /show or /register depending on status
/login redirects to /signup if user not registered
/signup redirects to /register upon signup. (signup form requires form validation)
/register redirects to /show upon registration success or /register if there's an error along with the error
