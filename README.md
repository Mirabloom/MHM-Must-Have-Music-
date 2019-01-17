## Abstract

MHM is a multi-platform application which allows the users to download the music and arrange it in the way they like/prefer, by genre, last added, artist, album, personalised playlist and favorites.The user can browse for a special genre of music or most popular or artist, etc... using variable combinations for searching.

## Purpose and Features

#### Purpose

Main purpose of this project are:
* Having an application that stores music and where a user can interact with it
* Create user friendly design
* Offers new features for having presonalised, smart playlists


#### Features

This multi-platform application has multiple features regarding having an online music library
* Ability to add a presonalised playlist or saving a public existing playlist
* Ability to search music by different combinations (example: by song, by artist, by genre)


## Tools and Technologies



### Prototyping Tools
Used application : 
* [Adobe Ilustrator CC 2015](https://www.adobe.com/products/illustrator.html)
* [Adobe Photoshop CC 2015](https://www.adobe.com/products/photoshop.html)
* [Adobe XD](https://www.adobe.com/uk/products/xd.html)
* [Adobe XD Kits](https://www.behance.net/gallery/55462459/Wires-wireframe-kits-for-Adobe-XD)


Fonts:
* [Google Fonts](https://fonts.google.com/) Used Arial


## Functionality
Below it is described how the application works and all the interactions with different users.

###  Users
Main types of users in the application:
* Unregistered user
* Registered user


### What a user can do?

Unregistered user can:
* Search for songs:
  * Search for a song based on artist name
  * Search for a song based on song name
  * View public playlists 
  * Listen to songs
* Page access:
  * Access to Home page (Home page include Browse section, where a user can access different types of categories: popular, rock, etc...)
  * Access to Search section
  
Registered user can:
* Search for songs:
  * By artist
  * By song
  * By genre
  * By album 
* Manage playlists:
  * Create a playlist public or private
  * Delete a playlist
  * Add songs to the playlists
  * Delete a song from the user playlists
  * Save a public playlist
  * Order songs in a playlist
  * Listen to songs saved and unsaved
* Page access:
  * Access to Home page (Home page include Browse section, where a user can access different types of categories: popular, rock, etc...)
  * Access to Search section
  * Access to Library page



##  Functional Description

### Security
##### Registration

1. New user = unregistered
2. Home page 
3. Click on Sign Up button
4. Enter personal data
5. Click on Submit


##### Login

1. Registered user
2. Home page 
3. Click on Sign In button
4. Enter username and password
5. Click Ok


##### LogOut

1. Registered user
2. Logged in user
3. Any accesible page 
4. Click on user dropdown menu from sidebar
5. Click on Logout button
6. Click on Ok button


### Playlists Interactions as a registered user
##### Create a playlist

1. A registered and logged in user
2. Click on Playlists dropdown list 
3. Click on 'Create playlist' button
4. Write down the playlist name
5. Select privacy type (Private or Public)
6. Press 'Save' button


##### Save a public playlist

1. A registered and logged in user
2. Select a public playlist
3. Press 'Save playlist' button


##### Add a song to playlist

1. A registered and logged in user 
2. Open a song
3. Click on 'Add to playlist' button
4. Select from the dropdown list wanted playlist


##### Deleting a song from playlist

1. A registered and logged in user 
2. Has songs in the playlist
3. Select a song
4. Click on 'Remove from playlist' button


##### Order songs in a playlist

1. A registered and logged in user 
2. Has songs in the playlist
3. Select a song
4. Drag the song and drop it where the user want


### Home page Interactions as a registered/unregistered user
##### Browse for songs

1. A registered and logged in user
2. Click on Home page 
3. A new page will be opened showing different categories
4. Select a category
5. A new page will open with different subcategories
6. Select a song


## User Interface

### Fonts and Colors

#### Fonts: [Arial](https://www.fonts.com/font/monotype/arial?QueryFontType=Web&src=GoogleWebFonts)

![Colors](/MHM-WEBSITE-COLOR-PALETTE.png)

### Design Message
Our brand is based on:
* Logo
* Main application features
* [3 main colors used in design](https://www.htmlcsscolor.com/)
  * Red as blood #FF0000
  * White #FFFFFF 
  * Black # 04040C


### Logo

The idea behind the design incorporates themes related to music and miscellaneous items (the µ letter of the Greek alphabet, the 12th letter) as well as encompassing the love for music.
The obvious marks are firstly the heart, as said exposing the love for listening to music, then the beamed music note ♫ that is used in music to connect multiple quaver notes. 

It also expresses the heart beat using the electromagnetic waves of the radio (frequency) when transmitting music, that can be sometimes mistaken for a pulse from the medical field at its highest. The frequency is connected by the letter µ because it means water, the property of music flowing like water.

The logo incorporates 2-3 main colors. The color red was chosen in the detriment of blue, as to signify the pulse and the heart.

![Logo](/Logo.png)

There are two additional themes: The C purple toned theme and the M pink toned theme.

![Logo](/Themes.png)
![Logo](/Colors.png)

The color red was chosen in the detriment of blue, as to signify the pulse and the heart. The additional C and M color themes were chosen as the colors favored by the creators.

![Logo](/Storming.png)

Below is the highlighted process of creation for the logo, from the trembly lines to vector, using Adobe CC 2015.

![Logo](/Scratch.png)


## Organization

This site is organized as below:
* Home
  * Genre
  * Most popular
  * New added
  * Artists
* Search
* Library  

Items pages:
  * Songs
  * Playlists
  
User Dropdown pages:
* User page
  * My Profile
  * My Playlists
  * Log out
  
 
## Methods:

For developing our music application we need the technical structure which is based on REST services, External API and Cloud SQL service for the Database. The website client is developed in Adobe XD. By applying Last.Fm which is a REST based service that uses the XML and JSON formatted responses we can interface with it through its methods.

 Why we used Last.Fm? Because it is a social website specialized in music recommandation. It pays attention to the music preferences of the users and offers them recommended new songs based on their taste and information about their favorite atrists. All the information is collected using Cloud storage service that is stored in PostgreSQL.


## XSPF:

XSPF is the XML format for sharable playlists and has the following qualities:
* Its is portable, a playlist can be used and carried from one place to another
* It is bug free, most playlists are full of bugs
* It is free and open


## JSON

JSPF is JSON XSPF. The definitions of JSPF fields follow from the XSPF specification, but the expression uses Javascript. By using JSON, the application is able to receive and send responses from API to Micro services.


## Our diagrams:

![Application diagram](/application-diagram.png)
![Package diagram](/package-diagram.png)
![Use Case diagram](/use-case-diagram.png)


## Prototype:
* Online Prototype: [MHM Prototype]( https://xd.adobe.com/view/3bcb0772-d38f-48af-7349-6d5d9e79b4b7-4dfa/?fullscreen)
* Design specifications: [Design Specfications](https://xd.adobe.com/spec/40f0cb47-14f4-48fb-615d-e6dbf19e948e-36c1/)


## Adobe XD plugins used to generate the code:

* Inker8 plugin code generator
* Web Export
* Copy CSS to clipboard
* Convert SCCS Variables
* Copy SVG Code


## References:
* [Last.Fm](https://www.last.fm/api)
* [XSPF](http://xspf.org/)
* [JSON](http://xspf.org/jspf/)
