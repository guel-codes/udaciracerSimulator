# Racing Simulator

## Project Introduction

The game mechanics are this: you select a player and track, the game begins and you accelerate your racer by clicking an acceleration button. As you accelerate so do the other players and the leaderboard live-updates as players change position on the track. The final view is a results page displaying the players' rankings.

The game has three main views:

1. The form to create a race

2. The race progress view (this includes the live-updating leaderboard and acceleration button)

3. The race results view

## Starter Code

We have supplied you with the following:

1. An API. The API is provided in the form of a binary held in the bin folder. You never need to open the binary file, as there are no edits you can make to it. Your work will be 100% in the front end.

2. HTML Views. The focus of this course is not UI development or styling practice, so we have already provided you with pieces of UI, all you have to do is call them at the right times.
<br>
<br>
### Start the Server

| Your OS               | Command to start the API                                  |
| --------------------- | --------------------------------------------------------- |
| Mac                   | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-osx`   |
| Windows               | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server.exe`   |
| Linux (Ubuntu, etc..) | `ORIGIN_ALLOWED=http://localhost:3000 ./bin/server-linux` |


<br>
#### WINDOWS USERS -- Setting Environment Variables
If you are using a windows machine:
1. `cd` into the root of the project containing data.json 
2. Run the following command to add the environment variable:
```set DATA_FILE=./data.json```

### Start the Frontend

First, run your preference of `npm install && npm start` or `yarn && yarn start` at the root of this project. Then you should be able to access http://localhost:3000.


### API Calls
 The API calls for this project were meant to fetch data from the datafile (data.json) and post the results to the server on localhost:8000. Each race that is ran will be pushe to the server using a post.

<br>
<br>

### Next Steps:
<ol>
<li>Tweak the front of the game to have a theme (I'm thinking F1)</li>
<li>Refactor and clean up some of the code. Move the API calls and other items into files of their own and import them as needed</li>
</ol>