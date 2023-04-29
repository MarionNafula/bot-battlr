# React Immersive Code Challenge: Bot Battlr

Welcome to **Bot Battlr**, the one and only spot in the known universe where you
can custom build your own Bot Army! This is our app:
can custom build your own Bot Army! 

![checkpoint demo](https://curriculum-content.s3.amazonaws.com/phase-2/phase-2-hooks-code-challenge-bot-battlr/checkpoint_demo.gif)

Here's the scenario: a galactic overlord has hired you, a galactic web
developer, to develop a galactic web app that will allow them to browse through
a list of robots, view a robot's details, and, enlist a bot into their army.

## Instructions

For this project, you’ll be building out a React application that displays a
list of available bots, among other features. Try your best to find the right
places to insert code into the established code base.

Part of what this code challenge is testing is your ability to follow given
instructions. While you will definitely have a significant amount of freedom in
how you implement the features, be sure to carefully read the directions for
setting up the application.

## Setup

After unbundling the project:
After forking the project:

1. Run `npm install` in your terminal.
2. Run `npm run server`. This will run your backend on port `8002`.

Endpoints for Core Deliverables
#GET /bots

Example Response:

[
  {
    "id": 101,
    "name": "wHz-93",
    "health": 94,
    "damage": 20,
    "armor": 63,
    "bot_class": "Support",
    "catchphrase": "1010010101001101100011000111101",
    "avatar_url": "https://robohash.org/nostrumrepellendustenetur.png?size=300x300&set=set1",
    "created_at": "2018-10-02T19:55:10.800Z",
    "updated_at": "2018-10-02T19:55:10.800Z"
  },
  {
    "id": 102,
    "name": "RyM-66",
    "health": 86,
    "damage": 36,
    "armor": 77,
    "bot_class": "Medic",
    "catchphrase": "0110011100000100011110100110011000011001",
    "avatar_url": "https://robohash.org/quidemconsequaturaut.png?size=300x300&set=set1",
    "created_at": "2018-10-02T19:55:10.827Z",
    "updated_at": "2018-10-02T19:55:10.827Z"
  }
]
