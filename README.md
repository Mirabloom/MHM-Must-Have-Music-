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


Icons sets (glyphicon, font awesome): To be modified
* [Iconify](https://iconify.design/)
  * [Font Awesome 4](https://iconify.design/icon-sets/fa/)
* [Flaticon](https://www.flaticon.com/)
  * [Gastronomy Set](https://www.flaticon.com/packs/gastronomy-set)
  * [Allergenic Food](https://www.flaticon.com/packs/allergenic-food)

Fonts:
* [Google Fonts](https://fonts.google.com/) To be modified




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
  * View puclic playlists 
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

### Fonts and Colors To be modified all

#### Fonts: [Quicksand](https://fonts.google.com/specimen/Quicksand)

![Colors](/_source/images/colors.png)

### Design Message
Our brand is based on:
* Logo
* Main application features
* 3 main colors used in design
  * Gray and its shades
  * White
  * Golden


Combination of Gray and white is the base of all application design, golden is used as a button color for succes buttons(Add to basket,Order,Save changes etc),r ed is used as a attention color(color for  food allergens).Gray and white combination are soothingly for user and golden is a succes color who push user to act, in our case to order a pizza or other food. 

### Logo

Logo Diana add 

![Logo](/_source/images/logo.png)

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
