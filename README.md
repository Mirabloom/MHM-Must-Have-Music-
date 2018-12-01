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


###  Functional Description

#### Authorization
##### Register
- [ ] Registered

1. Any accesible page 
2. Click on Sign In button
3. Click on Register button
4. Enter personal data
5. Wait for succes response

##### Login
- [x] Registered

1. Any accesible page 
2. Click on Sign In button
4. Enter username and password
5. Wait for succes response

##### LogOut
- [x] Registered
- [x] Logged

1. Any accesible page 
2. Click on user dropdown menu from sidebar
3. Click on Logout button

#### Basket Interactions as a registered user
##### Add item to Basket
- [x] Registered
- [x] Logged

1. Any page with product items
2. Click on 'Add to basket' button

##### Delete item from Basket
- [x] Registered
- [x] Logged
- [x] Having items in Basket

1. Any accesible page 
2. Click on 'Basket' image/button from sidebar
3. Click on 'X'-delete button on selected item

##### Clear Basket
- [x] Registered
- [x] Logged
- [x] Having items in Basket

1. Any accesible page 
2. Click on 'Basket' image/button from sidebar
3. Click on 'Clear' button

##### Send Order
- [x] Registered
- [x] Logged
- [x] Having items in Basket

1. Any accesible page 
2. Click on 'Basket' image/button from sidebar
3. Click on 'Order' button

#### Group Order as a order admin
##### Create Group Order
- [x] Registered
- [x] Logged

1. Any accesible page 
2. Open user dropdown menu from sidebar
3. Click 'Group Order' menu item
4. Add valability time
5. Click 'Save' button

##### Save Group Order
- [x] Registered
- [x] Logged
- [x] Created Group Order

1. Any accesible page 
2. Click 'Group User' image/button from sidebar
3. Modify all you wont
4. Click 'Save' button

##### Add User to Group Order
- [x] Registered
- [x] Logged
- [x] Created Group Order

1. Any accesible page 
2. Click 'Group User' image/button from sidebar
3. Click 'Add User' button from 'Users Orders'
4. Enter user data
5. Click 'Save' button

##### Delete User from Group Order
- [x] Registered
- [x] Logged
- [x] Created Group Order

1. Any accesible page 
2. Click 'Group User' image/button from sidebar
3. Click 'Delete User' button from selected user group
4. Click 'Save' button

##### Add Items for user order(part of group order)
- [x] Registered
- [x] Logged
- [x] Created Group Order

1. Any accesible page 
2. Click 'Group User' image/button from sidebar
3. Click 'Add Item' button from selected user group
4. Select Item
5. Click 'Save' button

##### Delete Items for user order(part of group order)
- [x] Registered
- [x] Logged
- [x] Created Group Order

1. Any accesible page 
2. Click 'Group User' image/button from sidebar
3. Click 'X' - delete button from selected item 
4. Click 'Save' button

#### Basket Interactions as a group order user
##### Add item to Basket
- [x] Registered
- [ ] Registered
- [x] Logged
- [ ] Logged
- [x] used valid Group Order link

1. Any page with product items
2. Click on 'Add to basket' button

##### Delete item from Basket
- [x] Registered
- [ ] Registered
- [x] Logged
- [ ] Logged
- [x] used valid Group Order link

1. Any accesible page 
2. Click on 'Basket' image/button from sidebar
3. Click on 'X'-delete button on selected item

##### Clear Basket
- [x] Registered
- [ ] Registered
- [x] Logged
- [ ] Logged
- [x] used valid Group Order link

1. Any accesible page 
2. Click on 'Basket' image/button from sidebar
3. Click on 'Clear' button
##### Add order to group order
- [x] Registered
- [ ] Registered
- [x] Logged
- [ ] Logged
- [x] used valid Group Order link

1. Any accesible page 
2. Click on 'Basket' image/button from sidebar
3. Click on 'Add to Group Order' button

## User Interface

### Fonts and Colors

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

Logo ilustrate using text and image one of the main feature of application - Ability to construct own pizza 

![Logo](/_source/images/logo.png)

### Navigation and Organization
For fastest and confortable navigation is used a navbar with all important pages shortcuts. Navbar can have multiple states for register user, unregister user, group order user

This site is organized on following pages:
* Home
* Menu
  * Pizza
  * Salad
  * Desert
  * Drinks
  * Vegan
* Promotions  
* Pizza creation

Items pages:
  * Pizza
  * Other Food/Drink
  
User Dropdown pages:
* User page
  * My Profile
  * My Orders
  * My Recipes
* Group Order
