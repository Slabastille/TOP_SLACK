# TOP SLACK PHASE 1

## Team Members:

Samuel Labastille

## Features

**Vision:**
Phase 1

- Slack App that creates a podium of the top three users in a slack channel with the most reactions on a message.
  Phase 2
- Slack App that creates a podium of the top three users in a slack channel who respond to the most message requests in a given channel. ie: ( it works channel, tools team channel)

**Features:**

- **MVP Features**

  - Time

    - Can select the time range of messages to look through
      - 1 day
      - 1 week
      - 1 Month
      - 1 Year

  - Message Count

    - Can select the amount of messages to look through

  - Channel
    - [ ] User can select channel to look into
    - [ ] User can add new channel to a database to look into

- **Bonus Features**

## Views

Add Bonus views here

## Wireframes

Add wireframes here

## Design

Add database schemas

## Customize

Now that you've got the code, follow these steps to get acclimated:

- Update project name and description in `package.json`, this is your database

## Start

Sync and seed your database by running `npm run seed`. Running `npm run start:dev` will make great things happen!

- start:dev will both start your server and build your client side files using webpack
- start:dev:logger is the same as start:dev, but you will see your SQL queries (can be helpful for debugging)
- start:dev:seed will start your server and also seed your database (this is useful when you are making schema changes and you don't want to run your seed script separately)
