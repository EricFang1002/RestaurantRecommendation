# Restaurant Recommendation System – Java Web Service Development

Sept. 2016 – Nov. 2016

This project is to provide a web service for users to search nearby restaurants and view recommended restaurants based on search history and user preferences.

## Back-End:
* Built a web service using Java Servlets to handle HTTP requests and responses.
* Utilized MySQL (relational database) to store user preferences and restaurant information fetched from Yelp API.
* Implemented a content-based recommendation algorithm to suggest similar restaurants based on restaurant categories.
* Improved precision of recommendation by ranking restaurants based on distance and matched categories.
* Deployed the website server on Amazon EC2 and evaluated the website with Junit (unit tests) and JMeter (load tests) which achieves 150 queries per second (QPS) tested by Apache JMeter.

## Front-End:
* Implemented a dynamic web page using AJAX techniques (HTML, CSS and JavaScript) for users to search nearby restaurants, update user preferences and view recommended restaurants.
* Designed an Android mobile application collaboratively to provide restaurant search service for users based on locations.

## Demo:
* User login
 
![Alt text](/images/user_login.jpg?raw=true "User Login")

* Retriving and loading the restaurant information from Yelp API

![Alt text](/images/loading.jpg?raw=true "loading")

* The system automatically shows the nearby restaurants around the users based on his/her position (longitute and latitute)

![Alt text](/images/near_restaurants.jpg?raw=true "near_restaurants")

* If the user moves the cursor onto a specific restaurant entry, the background color changes to white automatically

![Alt text](/images/up.jpg?raw=true "up")
