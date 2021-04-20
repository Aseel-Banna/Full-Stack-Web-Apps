# Lab: 11 - Spring for Full-Stack Web Apps

In this lab, we used Spring to build a full stack web app. So, we used controllers to define the routes using ***@GetMapping("/route")*** annotation. 

Structure:
* Album: this is a class that contains title, artist, length, song counts and image url. And I defined setters and getters for them.
* AppController: it is used to define **/hello** route and **/capitalize/{sentence}** route.
* SongrController: it is used to make three instances of albums and add them to a list and then render them in HTML file.

Also, there is a test file to test Album class with their setters and getters.


# Lab: 12 - Spring RESTful Routing

In this lab, I updated Album model so that it can be saved in a database. Also, I allowed the user to see information about all the albums on the site, and add albums to the site.

Structure:
* Album: this is a class that contains title, artist, length, song counts and image url. And I defined setters and getters for them. Also, it has an id.
* AlbumRepository which is extended from CRUDRepository.
* SongrController: which has a route for ***albums*** it will display all albums in data base. Also, there is ***addAlbum*** route which has a form to add an album to the database.



# Lab:  - Related Resources and Integration Testing

In this lab, I have created a new model for songs and create a relation between them and albums model.

Structure:
* Album: this is a class that contains title, artist, length, song counts and image url. And I defined setters and getters for them. Also, it has an id.
* AlbumRepository which is extended from CRUDRepository.
* SongrController: which has a route for ***albums*** it will display all albums in data base. Also, there is ***addAlbum*** route which has a form to add an album to the database.
* Songs: this is a class that contains title, length and track number. And I defined setters and getters for them. Also, it has an id, and it is related to albums.
* AlbumRepository which is extended from JpaRepository.
* * SongController: which has a route for ***songs*** it will display all songs in data base. Also, there is ***addSong*** route which has a form to add a song to the database.