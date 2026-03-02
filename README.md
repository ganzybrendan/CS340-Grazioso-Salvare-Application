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


