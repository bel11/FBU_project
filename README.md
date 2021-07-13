# FBU Project
Ideas
===

# Travel Route

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)
2. [Schema](#Schema)

## Overview
### Description
App that given several locations, finds the shortest path that lets the user visit each location. Especially given the pandemic, more people are visiting national parks - for users who want to road trip to several parks and are looking to determine the order to visit them, this app will return the path with the shortest total distance.

### App Evaluation
[Evaluation of your app across the following attributes]
- **Category:** Travel
- **Mobile:** More convenient to use mobile and find transportation more easily.
- **Story:** Users who want to travel would use this app to find the cheapest flights/busses to reach their destination.
- **Market:** Anyone who wants to travel.
- **Habit:** Used anytime someone wants to travel.
- **Scope:** Start out as finding shortest path by distance and add more features, such as calculating the path based on time, if there's time.

## Product Spec

### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* can log in & log out of app
* can save multiple groups of locations & displays the total distance to travel
* can click on locations combinations to see details about route
* can enter multiple groups of locations
* given start and end locations, outputs the order which the parks should be visited

**Optional Nice-to-have Stories**

* output path based on shortest time & display estimate of total time to travel
* factor in traffic into shortest time
* display the total route on a map
* filter itineraries based on total distance

### 2. Screen Archetypes

* log in
   * log into app
* list of current itineraries
   * can save multiple groups of locations & displays the total distance to travel
* can see details about travel plan
    * can click on locations combinations to see details about route
* enter start and end locations & loading screen
    * can enter multiple groups of locations

### 3. Navigation

**Tab Navigation** (Tab to Screen)

* list of current locations
   * GET - query all itineraries
* enter start and end locations & loading screen
   * POST - create a new itinerary

**Flow Navigation** (Screen to Screen)

* list of current start and end locations
   * tapping each list of location pairs
   * goes to details screen - GET - query details
* enter locations & loading screen
   * after entering - CREATE - create itinerary and destination
   * goes to details screen

![image](https://user-images.githubusercontent.com/67809754/124814786-6d4d2d80-df34-11eb-996c-b439a637fce8.png)
![image](https://user-images.githubusercontent.com/67809754/125088909-e024e880-e09b-11eb-81f0-45b76fffda89.png)
![image](https://user-images.githubusercontent.com/67809754/125088776-c08dc000-e09b-11eb-81af-ce9723a6df02.png)
![image](https://user-images.githubusercontent.com/67809754/125088801-c71c3780-e09b-11eb-9d53-1a93aae2a0fe.png)
