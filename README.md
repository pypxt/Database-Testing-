# Database-Testing-
Database Testing In The Context Of Software Quality Assurance

This project is focused on testing of the database 'dvdrental.tar'. It is a DVD Rental Management System. Testing required a combination of manual and automated testing techniques. It consists of 15 tables: actor, address, category, city, country, customer, film, film_actor, film_category, inventory, language, payment, rental, staff, store. 

We completed five types of testing:

- Data Validity Testing
- Performance Testing
- Security Testing
- Backup and Recovery Testing
- Data Migration Testing

Setup.
To perform the database testing we used such tools as: JMeter, PgAdmin, PostgreSQL, Jira, DBUnit.

Firstly, we created test plans and test cases in Jira. Using
Zephyr for Jira it made up possible to manage the testing process and write queries
and test scripts in advance. Using tool like Apache Junit we performed the
performance testing for our database dvdrent. It showed the positive expected
results. Using SQLMap it was possible to conduct security testing. We test if
database is easily manipulated and can be successfully backup and restore again.
Overall our database passed all tests and is responsible and well-structured.
