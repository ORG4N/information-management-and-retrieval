<<<<<<< HEAD
# COMP2001 
A repo for use for the COMP2001 Information Management &amp; Retrieval Module

=======
# COMP2001 Information Management & Retrieval
This repository has been used for Assignment 2 (70%) within the above module.

## Part 1
https://github.com/Plymouth-University/comp2001_assignment-ORG4N/tree/main/Task%201

This part of the coursework included making the following deliverables:
<ul>
  <li>A Microsoft SQL database</li>
  <li>An API to interact with the database</li>
</ul>

The database contains several tables that represent the three following entities: Students, their Projects, and the Programmes that they are enrolled within. The database also contains Stored Procedures and Triggers to provide speciifc behaviours. The following were created to meet the Assessment criteria:

The following tables were created:
<ul>
  <li>Students</li>
  <li>Programmes</li>
  <li>Projects</li>
  <li>StudentProgrammes</li>
  <li>StudentProjects</li>
  <li>Audit</li>
</ul>

Three stored procedures were then created to represent the following actions: Create, Update, Delete.
A student and their programme information can be found within a the StudentDetails view.
Finally, upon updating a Programme, a trigger would be called to store the old data in the Audit table, before it is overwritten by the new changes.

### API
An API was written in ASP.NET to interact with this database, by using the following HTTP methods: POST, GET, PUT, DELETE.

---

## Part 2
Part 2 of the assignment involved making a Linked Data Application. 

The dataset chosen to theme the project around was: Active Library User age statistics: 
https://plymouth.thedata.place/dataset/active-library-users-by-age

This part of the assignment involved reading data from a file and displaying it on a webpage. Reading the data involved writing a filereader in C#, using ASP.NET .
The data is written to the DATA webpage after being fetched via javascript scripts, and then dynamically written to a table, again using javascript.

The LDA includes three total webpages:
<ul>
  <li>Index - introduces application</li>
  <li>Data  - displays dataset information</li>
  <li>Borrowers - displays dataset information in JSON-LD format</li>
</ul>
>>>>>>> 7c15fc5602d1c42e602b6358878f408e082ffe6d

Bootstrap has been used to style the webpages: https://getbootstrap.com/
The dataset chosen to theme the project around was: Active Library User age statistics: https://plymouth.thedata.place/dataset/active-library-users-by-age
