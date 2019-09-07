# Ap&eacute;rio

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Aperio is the place you go to buy any local paintings or craftsmanship made with passion from 100% local artists.

### App Evaluation

- **Category:** Art & Design
- **Mobile:** This app is primarily developed for mobile in order to be available everywhere and anytime to the user.
- **Story:** Apério is an online market where anyone can buy handicraft work from local artists. The app help you find the closest art shops or artisan nearby, it let's you browse their available products and communicate with them to negotiate. 
- **Market:** Any individual could choose to use this app, and to keep it a safe environment, people would be organized into age groups.
- **Habit:** This app could be used as often or unoften as the user wanted depending on their needs, and what exactly they’re looking for.
- **Scope:** This could start a "*Nearby art seller finder*" type of app but perhaps later could evolve as an online seller exclusively made for atisans. Thus creating a large network of artisans, which would be beneficial to them and to the end user.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* Nearby vendors can be found on a map
* User can browse a vendor's products
* User can add product to cart
* User can see cart contents
* User can pay for product via external payment providers.
* Vendor can add product(with product details)
* Vendor can create an account
* Vendor can login to account
* Vendor can add account informations(Location, name, profession...) within account creation

**Optional Nice-to-have Stories**

* User can search by category or region
* User can search for a specific vendor
* User can signup/login to app
* User stay connect after leaving the app(session)
* User can save favorited items


### 2. Screen Archetypes

* Login screen
   * Vendor can login to account
* Registration screen
   * Vendor can create an account
* Mapview screen
    * Nearby vendors can be found on a map
* Stream screen
   * user can see cart contents
* Detail screen
   * User can browse a vendor's products
   * User can pay for product via external payment providers.
* Creation screen
   * Vendor can add product(with product details)
   * User can add product to cart
* Profile screen
   * Vendor can add account informations(Location, name, profession...) within account creation 


### 3. Navigation - User

**Tab Navigation** (Tab to Screen)

* Mapview screen

**Flow Navigation** (Screen to Screen)

* Login
   * Mapview screen
   * Registration screen
* Registration
   * Mapview screen
   * Login screen
* Mapview screen
   * Vendor detail screen
   * Cart screen
   * (To user info page, but this is a later feature)
* Search screen
    * Product detail screen
    * Mapview screen

### 4. Navigation - Vendor

**Tab Navigation** (Tab to Screen)

* Mapview screen
* MyProduct screen

**Flow Navigation** (Screen to Screen)

* Login
   * Mapview screen
   * Registration screen
* Registration
   * Mapview screen
   * Login screen
* Mapview screen
   * Vendor detail screen
   * Cart screen
   * (To user info page, but this is a later feature)
* Search screen
    * Product detail screen
    * Mapview screen
* MyProduct screen
    * Add product screen
    * Mapview screen


## Wireframes
<img src="https://i.imgur.com/DX3Y6zU.jpg" width=600>

### [BONUS] Digital Wireframes & Mockups
<img src="https://i.imgur.com/SK0SPx5.png" width=200>
<img src="https://i.imgur.com/dSDAvk7.png" width=200>
<img src="https://i.imgur.com/y8Vzb0B.png" width=200>
<img src="https://i.imgur.com/pzBc37M.png" width=200>
<img src="https://i.imgur.com/qjUbNzQ.png" width=200>
<img src="https://i.imgur.com/1f24OLJ.png" width=200>

### [BONUS] Interactive Prototype

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
