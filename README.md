Unit 8: Group Milestone 
===

# WORKOUT 

## Table of Contents
1. [Overview](#Overview)
1. [Product Spec](#Product-Spec)
1. [Wireframes](#Wireframes)

## Overview
### Description
iOS apps that helps users take better selfies


### App Evaluation
- **Category:** Fitness
- **Mobile:** This app would be primarily developed for mobile.
- **Story:** Users can find workout buddies and log their workout stats.
- **Market:** Any individual who wants to find accountability partners or track their workouts.
- **Habit:** This app could be used as often as user works out.
- **Scope:** First we would like implement the workout tracker feature, then if possible, introduce social features.

## Product Spec
### 1. User Stories (Required and Optional)

**Required Must-have Stories**

* User signup and login
* Table of last workout
* History of all past workouts
* Profile including goals

**Optional Nice-to-have Stories**

* In goals page, include graphs comparing current stats vs goals
* Progress photos and video form check
* Social feed
* Social map for finding gym buddies
* Next workout recommendation

### 2. Screen Archetypes

* Login Signup page
   * Upon login/sign up, open home page
* Home page
   * Upon starting new workout, displays recommended workout 'rep count' for current workout
* Profile page
   * Goals, user's own progress pics, history workouts
* Social feed
   * Feed of friend's progress pics

### 3. Navigation

**Tab Navigation** (Tab to Screen)
* Home
* Profile

Optional:
* Social

**Flow Navigation** (Screen to Screen)
* Login -> Opens home
* Add new post -> Opens camera/album

## Wireframes

User
| Property    | Type        | Description |
| ----------- | ----------- | ----------- |
| objectId    | String      |
| Username    | String      |
| Password    | String      |
| goalStats   | Dictionary  |
| trainingData| Dictionary  |

Posts
| Property    | Type        | Description |
| ----------- | ----------- | ----------- |
| objectId    | String      |
| Author      | String      |
| image       | String      |
| caption     | String      |

