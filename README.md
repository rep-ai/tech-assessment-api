# Technical Assessment

## Summary

Build an API service to manage a set of users.

## Details

Using Node and Typescript, build a web-based API which allows clients to manage a set of users. Please make regular commits with meaningful commit messages to a public GitHub repository, as you're working. Feel free to use any libraries you like and to take shortcuts, but be ready to explain your decision-making.

Please make sure to provide any necessary documentation & instructions to run the API locally and test the API routes.

## Requirements

The API should meet the following feature requirements:

### Create a user account

* Anyone can perform this task
* Users have a first name, last name, email address and password (you may add additional fields as you see fit)
* Only valid email address formats should be accepted
* The first user created (a fresh system should have zero users to begin) should be an "admin"

### Get details of a user account

* Only able to view the details of your own user account
* Admins can view details of any account

### Get a list of user accounts

* Only admins can perform this task

### Update user accounts

* Users can update their first name, last name, and password
* Admins can make other users admins

### Delete user accounts
* Users can delete their own account
* Admins can delete any account
* At least one admin must remain in the system

### View Endpoint Usage
* Only admins can view this data
* Accepts a time frame parameter to define the usage window
* Shows usage count of each endpoint for the usage window specified
