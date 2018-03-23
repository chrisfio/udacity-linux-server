# udacity-linux-server

## Introduction

Created to demonstrate my ability to build a full stack application, this is a Flask based CRUD web app hosted on an AWS Ubuntu machine using Apache with PostgreSQL. Layout built using CSS grid, login with OAuth2.0, and secured by Let's Encrypt

## Access

52.43.24.242 SSH Port: 2200

https://bartenderapp.chrisfiorino.com/

## Software Installed

For this project:
  1. I started with a 64 bit Ubuntu Linux Server from [Amazon Lightsail](https://lightsail.aws.amazon.com/)
  2. SSH into the server
  3. Update all packages. 
  4. Install the following:
    i. Apache
    ii. Flask
    iii. Let's Encrypt
    iv. PostgreSQL 
    v. Git
  5. Changed the SSH port from 22 to 2200 and updating the Lightsail account. 
  6. Created a new user named grader
  7. Gave the grader permission to sudo
  8. Created an SSH key pair for grader using the ssh-keygen tool.
  9. Configured the lcoal timezone to UTC
  10. Cloned my item catalog from Github
  11. Setup the server so that it displays the catalog when visiting my site.
  
I used resources found on:
  1. StackOverflow
  2. AWS Documentation
  3. Udacity Instructions and Lessons
  4. Digital Ocean Blogs
