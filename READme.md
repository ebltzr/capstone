# Capstone Name

Job Board - Size Up

## Learning Goals

Gain experience with full-stack web development using Django and front-end technologies
Learn how to integrate APIs into web application
Learn user authentication and authorization processes using Linkedin authentication and Google Auth

## Project Description

Application aims for job seekers to search for openings based on their qualifications, search filters provided by user track their job applications and receive personalized job alerts. It receives user information (education, experience, and skills) by creating a form for the user to input these details. 
**Possibly, use Linkedin authentication to allow users to authorize the application to access their data directly from Linkedin profile. Once authorized, make API calls to retrieve user education, experience, and skills and store them inside this database. **
The application will integrate with the Linkedin, Glassdoor and Indeed APIs to retrieve user information and job postings. Users will be able to login using their Google accounts (Google Auth), and their data will be stored in Django/Postgres database. 

Deployment on Render but looking into using Heroku.

## MVP Featureset

- **User will click "Sign in with Linkedin" button, 
- Redirect user to Linkedin Auth page
- User authorizes application to access Linkedin information
- Receive auth code and token***
-----------------------
- User will click "Sign in with Google Auth user redirected to Google Auth page, user logs in with their Google account credentials
- Allow users to search for job openings based on keywords, location and other criteria
- Allow users to save job searches  for future reference, send them to their email
- Recieve auth code and token from Google
-----------------------
- Store user information from sign in, in the database and create a session for the user
- Store and retrieve data (education, experience, skills) in the database
- Retrieve and display relevant job postings from the APIs
-----------------------
- Form for users to track  the status and store the details of their job applications

## Stretch Goals 

**Linkedin authentication to allow users to authorize the application to access their data directly from Linkedin profile. Once authorized, make API calls to retrieve user education, experience, and skills and store them inside this database. 
- "After authentication, LinkedIn's authorization server passes an authorization code to your application. Your application sends this code to LinkedIn and LinkedIn returns an access token." https://learn.microsoft.com/en-us/linkedin/shared/authentication/authorization-code-flow?tabs=HTTPS1 ***
- Store job application details in the database and display status on the users account page --  or allow users to manually update the status of their job application on the platform ie add section where users can mark their application as applied, in progress or closed

## Main Front-end Technology

- React
- Js Vanilla
- CSS

### Additional Front-End Technologies 

Looking into Bootstrap: front-end framework provides pre-designed templates and components for responsive web design

## Main Back-end Technology

Python - Django/Postgres

### Additional Backend Technologies 

Python-LinkedIn library: Python interface for Linkedin API for retrieving user information
Linkedin API: access their job posting and related data
Glassdoor API: access their job posting and related data
Indeed: access their job posting and related data

## Database

- PostgresQL

## Wireframe