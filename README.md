# Animal-Shelter-Management-System
About the Project/Project Title
This project is working to create an interactive dashboard for the rescue-animal training company, Grazioso Salvare. Through this dashboard users can look through all the dogs available in a specific rescue shelter and filter them to see candidates for specific search-and-rescue training. To make the dashboard more user friendly there are filter buttons to narrow down one’s search, a histogram that displays how many of each dog breed that matches the criteria are available, as well as show the location of the dog. 

Motivation
This project exists to make it easier to filter through a large amount of data. The filter buttons allow one to narrow down their search. The histogram makes it easier to visually see the options available, and the location chart allows one to instantly see where the dogs are located. This type of dashboard could be applied in any situation where one wants to filter through data making it very versatile. 

Getting Started
To get a local copy up and running, follow these simple example steps: 
1.	In your database upload a file that contains all the information you would like to access, here it is information on the animals at an animal shelter. 
2.	In your database create user authentication so that only those with the correct username and password can connect to your database and edit it. 
3.	Create a Python file that connects a user to their database and contains functionality for creating, reading, updating, and deleting information from it. 
4.	In another file create a dashboard that calls upon the Python file
5.	Add functionality to your dashboard as desired such as geolocation charts, tables displaying the database information, as well as visual charts. 
6.	Ensure it works by running it and testing the functionality. 

Installation
You will need:
A computer that can run Python code as well as your chosen database. 

Usage
Use this space to show useful examples of how your project works and how it can be used. Be sure to include examples of your code, tests, and screenshots.

Code Example
The code allows users to read information from their database and display it in a more organized manner. All of the animals from the shelter are placed into a data table, users can then select what type of dogs they want to see based on what they are looking for. To make processing the information easier a histogram and geolocation chart are also included. The histogram shows how many of each type of dog are available and updates as users select different filters. The geolocation shows where the dog is located so users can quickly verify which shelter it is at. 

Tests
To test the code all functionalities should be checked. Every filter should be selected and verify that it updates with the correct information. The reset filter should also be checked to make sure it does indeed remove all filters. The histogram should display information that corresponds to that on the table and update whenever a filter is selected. Manually check this by verifying that the table does match what is outputted on the histogram. The geolocation chart should show the dog at the top of the table. Manually hover over the location pin and check that the name does indeed match the dog at the top of the table. Also verify that any labels you want such as a title at the top of the page are correct, and that your image loads correctly if you chose to include one. 
