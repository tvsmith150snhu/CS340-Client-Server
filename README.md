CS 340 README 


About the Python application 

This application uses Python code to search the AAC database using MongoDB Query operators such as ‘$and’, ‘$gte’, ‘$lte’, etc to return desired criteria and display the results in an aesthetically pleasing manner that the user may view the results along with a graph of the searched value and location specifically selected items on an interactive map.  The .ipynb file imports functions defined in the .py file for CRUD functionality when ran in Jupyter Notebook.  

Motivation

The Grazioso Salvare Company uses this database dashboard to locate candidates of dogs to be trained for human and other animal rescues.  The database ingests data from five animal shelters in the region around Austin, Texas, while the dashboard application allows the company to search and sort the data in a manageable manner that displays the animal’s geographical location on the map and also provides a pie chart depicting the percentage of breed of animal.
 

Getting Started

The application consist of two files, ProjectTwoDashboard.ipynb and the animalshelter.py.  The user account must be configured for authentication to the database, in this example the “aacuser” is configured in the ‘admin’ database using password “password”.    
 
 


Once authentication is established and tested, the code from the ProjectTwoDashboard.ipynb may be entered into the Jupyter Notebook and named with the .ipynb suffix.  Be sure the animalshelter.py file and ProjectTwoDashboard.ipynb files are in the same directory and run the ProjectTwoDashboard file in Jupyter Notebook.  You should see the following displayed if successful.
 
 
 


Installation

Python 3.* must be installed
The Mongo database must be installed.


Contact
Troy Smith – troy.smith1@snhu.edu
 

Additional Screenshots

 
 

