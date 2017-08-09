# Creating Routes


## Objectives

- Create restful routes
- Examine HTTP methods and status codes
- Understand request and response


## REST

We are going to be following REST standards building this API.
With REST every resource in your application maps out to a route that can be accessed.
Think **User** resource with user routes, trips resource with routes for trips


## HTTP Methods



| Action  	| HTTP Verb 	| Path             	| Effect                           	        |
|---------	|-----------	|------------------	|-------------------------------------------|
| create  	| POST      	| /user/trips           	| Creates a new trip               	|
| index   	| GET       	| /user/trips           	| Shows/lists all trips            	|
| show    	| GET       	| /user/trips/<trip_id> 	| Shows a specific trip            	|
| update  	| PUT/PATCH 	| /user/trips/<trip_id> 	| Updates/replaces a specific trip 	|
| destroy 	| DELETE    	| /user/trips/<trip_id> 	| Deletes a specific trip          	|


## Route types

### Member Routes
Member routes
### Collection Routes



## Challenges