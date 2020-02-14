# console.love Project Proposal

## Overview

## User Stories

## Planned Workflow and Responsibilities

The console.love team will use a combination of Centralized and Feature Branch Git Workflows, with an emphasis on pair programming. Responsibilities will be distributed roughly as follows:

Jaimie - Project Manager - Backend + Testing - Deployment - React Router
<br>
Muezzin - Git Manager - Javascript Guru - Algorithm Wizard
<br>
Rixio - Ideas Guy - CSS Master - Comfortable in React

These responsibilities are based on team members' natural strengths. Each member will be working on both ends of the project. We plan to work on both things we are comfortable with and things that we struggle with, so that we each learn something new and improve areas that need it. All planning and task tracking will be handled through our Trello Team Board.  The team has set a rough schedule and will meet over Zoom. 

## Technologies
Front end:
- React, React Router
- Axios for API calls
- CSS Grid

Back end:
- Database
   - MongoDB
   - Mongoose
- Functionality
   - Express
   - Method-override
   - Lodash
- Connection between back and front ends
   - Cors
- Testing
  - Supertest
  - Chai
  - Mocha

## Wireframes

## Component Hierarchy

![Component Hierarchy Diagram](https://user-images.githubusercontent.com/57021062/74549055-92db3080-4f14-11ea-813d-ec4333c03d07.png)

## Profile Data Example

![Profile Document Example](https://user-images.githubusercontent.com/57021062/74544666-214bb400-4f0d-11ea-945c-6cb27dfb399e.png)

## Dataflow Diagram

## App Tiers

### Bronze (MVP)
- App optimized for mobile from outset
- Homepage displays 10 pictures (10 profiles in database)
- Each picture is a clickable link that takes user to a profile page
- The profile page contains: picture, age, name, location, about me, programming languages, Home button and Match button
- Match button takes you to a page that displays "It's a Match!" and a Home button
- Ability to create a profile on a separate page with a blank form
- Edit page with a pre-populated form where user can update or delete their profile

### Silver
- Pictures grid rotates every time site loads
- If you match, you can see their github link
- Refactor with Hooks
- Logo

### Gold
- User authentication
- Incorporate GoogleMaps location for profiles/user
- Messaging by id (users can chat with each other)
