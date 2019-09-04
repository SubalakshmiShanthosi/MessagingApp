# MessagingApp
Messaging Application in RESTFul Approach


# USE CASES


# 1. Purpose

This document provides the high-level requirements for building a Messaging Application. (Web
Application)

# 2. Functional Requirements

The application must meet the following requirements:

## A. User Registration

  ● Registration includes a name, email address, password and confirmation password.
  
  ● The app must have a redirect link for the user user to the login page.
  
  ● The application must reject a password which is less than 8 characters.
  
  ● The user email must be a new entry and only one email id should be used for one registration (one user).

## B. User Login
  
  ● Each user must have a separate login to the application. The login will be using an email address and a password
  
  ● The app must inform the user if the user is not registered
  
  ● The application must reject a wrong password

## C. View Users

  ● Once logged in, the users should be able to see other users of this application (whether or
not they are logged in / active).

  ● The user should be able to see other users (excluding him / herself) as a list on the left side
of the app along with their thumbnail profile photos

  ● There will be 2 lists – All users and Connected users (ones who have accepted the
connection request)

  ● Clicking on each user in the list will open a menu whether to:
              
              o View Profile (for all users)
              
              o Connect user (if user is already not connected)
              
              o Message user (only for connected users)
              
              o Delete Connection (only for connected users)

## D. View / Edit User Profile
  
  ● Clicking on ‘View User Profile’ will show their simple profile (fly out / modal)
  
  ● The profile view will show a Display Name, Email Address, and their photo on their profile.
  
  ● The profile can be editable, only if the user is logged in and should be updated in the
database as soon as the changes are made. 

## E. Messaging
  
  ● Users should be able to message other connected users
  
  ● Each message will appear in a message bubble along with responses
  
  ● The messages will appear in chronological order (both from and to messages) with the newest message in the bottom
  
  ● Users will have ability to delete a sent message and the bubble will show as a ‘Deleted message’
  
  ● Users will have ability to share text message or attach an image or an attachment
  
# 3. Other Requirements

  ## A. Look & Feel
    
  ● The messaging app should have a good UI

  ● It should be a web application

  ● Only Web application will be accepted.
 ## B. Architecture

  ● The app should have a front-end (UI), middleware, and a database to store & retrieve the
messages
  
  ● Preferred technologies / languages are HTML / CSS / Bootstrap & PHP or Angular Framework
from the front-end, Java REST APIs for the middleware and MySQL for the backend –
however, these are not mandatory
  
  ● Your codebase should have the same level of structure and organized as any mature open
source project including coding conventions, directory structure, a README.md with clear
instructions and additionally a runner shell script that automates the entire build and
execute process.

 ## C. Bonus points for 
 
  ● Message read / unread count
  
  ● Message marked as read when viewed
  
  ● Logged in users can edit this data for their own profile, using a simple modal than a dedicated page

  ● Verify the user after registration.
  
  ● Notifications on receiving a message.
  
  ## D. Guidelines

  ● Your codebase should have the same level of structure and organised as any mature open source project including coding    conventions, directory structure, a README.md with clear instructions and additionally a runner shell script that automates the entire build and execute process.
