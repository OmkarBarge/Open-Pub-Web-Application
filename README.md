# Open-Pub-Web-Application-using-Streamlit
- Google Map is down because of some issue, so main aim of this application was to provide a convenient way for users to explore pub 
 locations and find nearby pubs for a fun and enjoyable experience. <br>
- Preprocessed the dataset in Jupyter Notebook, handled null values in the latitude and longitude columns by removing the corresponding rows.<br>
- Created WebApp using Streamlit Framework which allowed for seamless creation of multi-page functionality. <br>
 The application included three main pages, each serving a specific purpose.<br>
  -- Home Page: This page welcomed users and render basic information and statistics about the dataset. It offered a brief overview 
 of the pub data, including the number of pubs available and any interesting insights derived from the dataset.<br>
  -- Pub Locations: On this page, users could input a postal code or local authority to view all the pubs in the chosen area. 
 The application used the latitude and longitude information from the dataset to display the pub locations on a map, providing a visual 
 representation of the pub distribution in the specified region.<br>
  -- Find the Nearest Pub: This page allowed users to enter their own latitude and longitude coordinates. Using the Euclidean distance 
 calculation, the application determined the five nearest pubs to the user's location. These nearest pubs were then displayed on the map,
 enabling users to easily identify and visit the closest options. <br>
 Technologies : Python, Streamlit

<hr>
Task - Open Pub Application


Let’s assume you are on a vacation in the United Kingdom with your friends. Just for some fun, you decided to go to the Pubs nearby for some drinks. Google Map is down because of some issues. 

While searching the internet, you came across https://www.getthedata.com/open-pubs. On this website, you found all the pub locations (Specifically Latitude and Longitude info). In order to impress your friends, you decided to create a web application with the data available in your hand. (Go through the requirements mentioned below)

Download data from here.
Click here to access the data dictionary.


Task - Create a multi page application using Streamlit with the following requirements.

Page Number 1 - (Home Page)
It should be like a welcome page. Show some basic information and statistics about the dataset.


Page Number 2 - (Pub Locations)
Display a map. Based on the Postal Code or Local Authority, display all the pubs in the area chosen. 

Page Number 3 - (Find the nearest Pub)
Ask the user to enter his/her Latitude and Longitude. Display the nearest 5 Pubs on the map. Use Euclidean Distance to find the nearest pubs.


Hint - There are some Null Values in the Latitude and Longitude Column. Use Jupyter Notebook to either impute the null values or delete the rows and then proceed with app development.
