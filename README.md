# Backend Engineer Challenge

Hello, 

Thank you for taking the time to complete this challenge. The goal here is to get a sense of your API design and implementation skills. This challenge does not aim at finding the perfect solution but rather to help us understand the depth of your knowledge in implementing APIs.  We suggest spending up to 4 hours on this task.

We wish you all the best and good luck!

## Challenge

Design and implement a REST API service that will choose a [Secret Santa](https://en.wikipedia.org/wiki/Secret_Santa) for all  your teammates.

Please zip your project folder with instructions for running your application and send it to francesca@aylien.com

If you have any questions about this challenge, please feel free to email them to: sergey@aylien.com

## Requirements

* Provide an API endpoint to register a new teammate
* Provide an API endpoint to collect a list of all Secret Santas for the selected year
* A person cannot be their own Secret Santa
* A person can only be the same other person’s Secret Santa once every three years (​​e.g. if in 2020 Martin was Julia's Secret Santa, Martin cannot again be  Julia's Secret Santa before 2023)
* Provide an OpenAPI Specification
* Document your solution

**Note:** 
* You can pass a selected year in the HTTP request 

## You are required to:
* Provide an appropriate evaluation of the secret santa algorithm  
* Create a REST service using the quarkus / spring framework
* Use relational database (MySQL / PostgreSQL / H2)
* Document instructions on how to build and run the service locally
* Create a container with your solution that can be run on Kubernetes
* Provide curl commands or a Postman collection for interaction with the service
