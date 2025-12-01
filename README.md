Original App Design Project - README Template
===

# GeoBuddy

## Table of Contents

1. [Overview](#Overview)
2. [Product Spec](#Product-Spec)
3. [Wireframes](#Wireframes)
4. [Schema](#Schema)

## Overview

### Description

[Provide a brief description of your app, its purpose, and functionality.]

### App Evaluation

[Evaluation of your app across the following attributes]
- **Category:** Education
- **Mobile:** This is only a mobile application.
- **Story:**  This app allows users to improve their geographical knowledge while incorporating real-life features.
- **Market:** This app is mainly for geography buffs, or anyone who would want to learn more about their surroundings. 
- **Habit:** This is an occasional use app.
- **Scope:** The scope of this app is narrow.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**
* User can view a map with a highlighted country or capital city
* User can guess a country name from a map location
* User can guess a capital city name from a map location
* User can see if their guess is correct or incorrect
* User can get their current location using GPS
* User can view information about their current location (city, country, coordinates)

**Optional Nice-to-have Stories**
* User can track their score or number of correct guesses
* User can choose between difficulty levels (easy, medium, hard)
* User can see a hint before making a guess
* User can share their location information
* User can save their favorite locations

### 2. Screen Archetypes

- [ ] **Home Screen**
  * Required User Feature: User can choose to play the guessing game or check their location
- [ ] **Map Guessing Game Screen**
  * Required User Feature: User can see a map with a highlighted location and guess if it's a country or capital
- [ ] **Guess Input Screen**
  * Required User Feature: User can type their guess and submit it
- [ ] **Results Screen**
  * Required User Feature: User can see if their guess was correct and view the correct answer
- [ ] **My Location Screen**
  * Required User Feature: User can see their current location on a map and view location details (city, country, coordinates)
- [ ] **Location Details Screen**
  * Required User Feature: User can view information about their current location

### 3. Navigation

**Tab Navigation** (Tab to Screen)
- [ ] Home Tab → Home Screen
- [ ] Game Tab → Map Guessing Game Screen
- [ ] My Location Tab → My Location Screen

**Flow Navigation** (Screen to Screen)
- [ ] **Home Screen**
  * Leads to Map Guessing Game Screen
  * Leads to My Location Screen
- [ ] **Map Guessing Game Screen**
  * Leads to Guess Input Screen
- [ ] **Guess Input Screen**
  * Leads to Results Screen
- [ ] **Results Screen**
  * Leads back to Map Guessing Game Screen (for next round)
- [ ] **My Location Screen**
  * Leads to Location Details Screen 


## Wireframes

[Add picture of your hand sketched wireframes in this section]

### [BONUS] Digital Wireframes & Mockups

### [BONUS] Interactive Prototype

## Schema 


### Models

[Model Name, e.g., User]
| Property | Type   | Description                                  |
|----------|--------|----------------------------------------------|
| username | String | unique id for the user post (default field)   |
| password | String | user's password for login authentication      |
| ...      | ...    | ...                          


### Networking

- [List of network requests by screen]
- [Example: `[GET] /users` - to retrieve user data]
- ...
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
