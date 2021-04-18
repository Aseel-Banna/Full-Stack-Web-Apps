# Lab: 11 - Spring for Full-Stack Web Apps

In this lab, we used Spring to build a full stack web app. So, we used controllers to define the routes using ***@GetMapping("/route")*** annotation. 

Structure:
* Album: this is a class that contains title, artist, length, song counts and image url. And I defined setters and getters for them.
* AppController: it is used to define **/hello** route and **/capitalize/{sentence}** route.
* SongrController: it is used to make three instances of albums and add them to a list and then render them in HTML file.

Also, there is a test file to test Album class with their setters and getters.