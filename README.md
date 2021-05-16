# Homework 17 - Workout Tracker

![GitHub followers](https://img.shields.io/github/followers/Walkerj90?logo=GitHub&style=plastic)
![npm](https://img.shields.io/npm/v/express?color=green&label=express&logo=NPM&style=plastic)
![npm](https://img.shields.io/npm/v/mongoose?color=orange&label=mongoose&logo=NPM&style=plastic)

![workout-tracker](https://user-images.githubusercontent.com/72112742/118412806-e1640700-b650-11eb-97e4-2a983f2f7bed.gif)

## Description

The goal for this assignment is to create a full stack workout tracker web application that will allow a user to keep track of their workout regime by using MongoDB and Mongoose schema for database creation/management and Express for handling routes.

The main focus for this assignment is to practice using MongoDB and Mongoose for database management, the front-end code was provided in the homework assignment's directory for us to leverage for this assignment.

## Links to Deployed application and Github Repo

- Link to GitHub Repo - [Workout Tracker Repo on GitHub](https://github.com/walkerj90/Fitness-Tracker)

- Link to deployed application - [Workout Tracker App deployed on Heroku](https://whispering-shelf-25680.herokuapp.com/stats)

---

## User Story

* As a user, I want to be able to view create and track daily workouts. I want to be able to log multiple exercises in a workout on a given day. I should also be able to track the name, type, weight, sets, reps, and duration of exercise. If the exercise is a cardio exercise, I should be able to track my distance traveled.

## Installation

All NPM packages needed for this application are already listed as dependencies in the `package.json` file. If running this web application in your local environment, please make sure to run the `npm install` command in your terminal at the root directory level in order to access all required package.

### Start Application

After all required dependencies have been installed, run the command `npm run start` in you the terminal under the root directory in order to launch the application. The screenshot provided below is what should outplu of the application is launched successfully in your local environment.

## Business Context

A consumer will reach their fitness goals more quickly when they track their workout progress.

## Acceptance Criteria

When the user loads the page, they should be given the option to create a new workout or continue with their last workout.

The user should be able to:

  * Add exercises to the most recent workout plan.

  * Add new exercises to a new workout plan.

  * View the combined weight of multiple exercises from the past seven workouts on the `stats` page.

  * View the total duration of each workout from the past seven workouts on the `stats` page.
