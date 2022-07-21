# Day 12 Workshop

### Introduction to Thymeleaf

Workshop Objective

#### A walkthrough of commiting & pushing to Github.

Importance of writing code on a development branch 
1. git checkout -b develop
2. git branch -a

#### Creating a Thymeleaf Page.

1. Visual Code > Java Projects under EXPLORER > src/main/java > + > input the class name
2. Getting current time by using model.addAttribute and display it on indexresource.html
3. Writing if-unless statement in Thymeleaf

#### Thymeleaf - Iteration
1. Building a model - Item.java (a sample data structure containing name,quantity etc) 
2. Creating a service class - CartService.java (contains a list of sample data input)
3. Creating a controller for the Cart - CartController.java
4. Creating a view - cart.html 

#### PathVariable & StringQuery
1. Utilising the @PathVariable (WeatherController.java)
2. Differences between StringQuery and PathVariable.
3. Usage of Postman to test GET request.

#### Number Generator Exercise
1. Files created (NumberController.java , number.html)
2. Using POST on the form method and define a range of values to generate (number.html)
