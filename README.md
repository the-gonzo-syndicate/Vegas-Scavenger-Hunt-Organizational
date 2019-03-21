# VEGAS SCAVENGER HUNT

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
Vegas Scavenger Hunt is an iOS Application created with Swift, by a student organization of The College of Southern Nevada. The app will lead users on various themed scavenger hunts throughout Las Vegas. They will take pictures of the required areas, earning points and badges for each place they visit. This would lead to many opportunities for advertising of nearby businesses and attractions.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Travel & Tourism / Interactive Gaming.
- **Mobile:** Uses camera and location data, mobile only.
- **Story:** Allows users to search Las Vegas for stops on defined scavenger hunts, where upon the user can log their stop, take a         picture, and gain points on the leaderboard. 
- **Market:** It will be heavily marketed towards the Travel and Tourism industry, which Las Vegas caters to around 40 million tourists   a year. It will aid in giving tourists who often do not know what to do in Las Vegas a multitude of exciting goals to achieve, but yet   will also be challenging for locals as well. Eventually would love to add advertisements and featured stops. 
- **Habit:** Users can gain points for the various stops they visit, and complete entire scavenger hunts, which can be quite addicting.   Being able to see your progress on a leaderboard of others will also add to it's addictiveness.
- **Scope:** The scope is focused to showing people interesting places and sights in Las Vegas from a tourism standpoint, but can also     be used to deliver advertising and specials at nearby establishments. 

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User can create a new account.
* User can login.
* User can view a profile page.
* User can view a leaderboard.
* User can scroll through a list of scavenger hunts.
* User can see details of a scavenger hunt.
* User can see details of a scavenger hunt stop.
* User can record visiting a scavenger hunt stop.
* User can take a picture at a scavenger hunt stop.
* User gains points for visiting places/completing scavenger hunts.

**Optional Nice-to-have Stories**

* User is greeted with an animated splash screen.
* User is shown an onboarding message upon first login.
* User recieves a video picture collage by email upon scavenger hunt completion.
* User can share scavenger hunt stop checkins on social media. 

### 2. Screen Archetypes

* Login Screen
   * User can create a new account.
   * User can login.
* Stream
   * User can scroll through a list of scavenger hunts.
* Profile
   * User can view a profile page.
* Detail
   * User can view a leaderboard.
* Detail
   * User can see details of a scavenger hunt.
* Creation 
   * User can see details of a scavenger hunt stop.
   * User can record visiting a scavenger hunt stop.
   * User can take a picture at a scavenger hunt stop.
   * User gains points for visiting places/completing scavenger hunts.

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* Profile
* Scavenger Hunt Feed
* Leaderboard

**Flow Navigation** (Screen to Screen)

* Login Page
   * => Scavenger Hunt Feed
* Scavenger Hunt Feed
   * => Scavenger Hunt Detail
* Scavenger Hunt Detail
   * => Scavenger Hunt Stop Detail
* Scavenger Hunt Stop Detail
   * => Scavenger Hunt Stop Creation

## Wireframes
**Digital Wireframe**

<img src="https://github.com/the-gonzo-syndicate/Vegas-Scavenger-Hunt/blob/master/Vegas_Scavenger_Hunt_Wireframe.PNG" width=600>

**Gif Wireframe Model**

<img src="http://g.recordit.co/LwVClP6G08.gif" width=400>


### [BONUS] Interactive Prototype

Interactive Prototype can be viewed here: https://www.figma.com/file/Xg2hfX2mlsesFcS4GWt4ukhp/Vegas-Scavenger-Hunt?node-id=0%3A1

## Schema 
[This section will be completed in Unit 9]
### Models
[Add table of models]
### Networking
- [Add list of network requests by screen ]
- [Create basic snippets for each Parse network request]
- [OPTIONAL: List endpoints if using existing API such as Yelp]
