# CS340-Grazioso-Salvare-Application

Brendan Ganzy
SNHU
CS340


					Project 2 ReadMe

This program is a python based dashboard web application for Grazioso Salvare. It allows users to create, read, update and delete animal records in a Mongo database. The application connects to the Mongo database, which contains animal shelter data from the AAC dataset. 



The purpose of this CRUD Animal Shelter application, is to to interact with stored data inside a Mongo database. In a manner where that information can be accessed, filtered and visualized through an interactive dashboard. The information that the database contains is the animal ID, animal type, breed, age, outcome type and geographic location.
The tools used for this application were python, MongoDB, dash framework and the jupyter notebook. 


The motivation behind this is to create an application that is able to access, store and retrieve data efficiently. We can see the usefulness of this in other real world applications like save files in video games and storing account credentials. In this case, the application is used to manage animals and their identification numbers for rescue classification and transfer to rescue training programs. 

The way the application works is that the MongoDB runs locally and the Austin Animal Center dataset is imported to the mongoDB. The CRUD module then connects to the database and retrieves all the animal records. The user is then able to interact with the controls in the application to transfer animals to different locations. Some challenges i ran into were some filters returning no data at times and the mapping with geolocation. 


-How do you write programs that are maintainable, readable, and adaptable? Especially consider your work on the CRUD Python module from Project One, which you used to connect the dashboard widgets to the database in Project Two. What were the advantages of working in this way? How else could you use this CRUD Python module in the future?
Writing programs that are maintainable and adaptable consist of focusing on reuse and big O notion, as well as readability of your code. In this program specificaly, these aspects were mainly focused on with the CRUD method in python. 


-How do you approach a problem as a computer scientist? Consider how you approached the database or dashboard requirements that Grazioso Salvare requested. How did your approach to this project differ from previous assignments in other courses? What techniques or strategies would you use in the future to create databases to meet other client requests?
As a computer scientist, I approached the problem of creating a dashboard application for Grazioso Salvare by analyzing the company's requirments which were database connection, data visualization and geolocation mapping. 

-What do computer scientists do, and why does it matter? How would your work on this type of project help a company, like Grazioso Salvare, to do their work better?
Computer Scientists create and maintain systems that provide services and tools, that provide the accessability for new inventions and the advancement of the human race. This project has the ability to help companies like Grazioso Salvare use the data that they collect to create, update, read and delete classifications and catagories that help better understand the information they have collected. 



