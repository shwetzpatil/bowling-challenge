
Bowling Challenge
=================

## Website link

[BowlingScoreBoard](https://bowlingscoreboard.netlify.com/)

## The Task

**THIS IS NOT A BOWLING GAME, IT IS A BOWLING SCORECARD. DO NOT GENERATE RANDOM ROLLS. THE USER INPUTS THE ROLLS.**

Count and sum the scores of a bowling game for one player (in JavaScript).

A bowling game consists of 10 frames in which the player tries to knock down the 10 pins. In every frame the player can roll one or two times. The actual number depends on strikes and spares. The score of a frame is the number of knocked down pins plus bonuses for strikes and spares. After every frame the 10 pins are reset.

## Installation Steps
1. Clone this repo
2. Run in browser `index.html`
## Run the test
1. Open the path `SpecRunner.html` in browser.

## Eslint
1.  `cd` to the root directory of the repo
2. Run in terminal
```
npm run eslint **/*.js
```

## Bowling — how does it work?

### Strikes

The player has a strike if he knocks down all 10 pins with the first roll in a frame. The frame ends immediately (since there are no pins left for a second roll). The bonus for that frame is the number of pins knocked down by the next two rolls. That would be the next frame, unless the player rolls another strike.

### Spares

The player has a spare if the knocks down all 10 pins with the two rolls of a frame. The bonus for that frame is the number of pins knocked down by the next roll (first roll of next frame).

### 10th frame

If the player rolls a strike or spare in the 10th frame they can roll the additional balls for the bonus. But they can never roll more than 3 balls in the 10th frame. The additional rolls only count for the bonus not for the regular frame count.

    10, 10, 10 in the 10th frame gives 30 points (10 points for the regular first strike and 20 points for the bonus).
    1, 9, 10 in the 10th frame gives 20 points (10 points for the regular spare and 10 points for the bonus).

### Gutter Game

A Gutter Game is when the player never hits a pin (20 zero scores).

### Perfect Game

A Perfect Game is when the player rolls 12 strikes (10 regular strikes and 2 strikes for the bonus in the 10th frame). The Perfect Game scores 300 points.

In the image below you can find some score examples.

More about ten pin bowling here: http://en.wikipedia.org/wiki/Ten-pin_bowling

![Ten Pin Score Example](images/example_ten_pin_scoring.png)

## Userstories

``` 
As a player
So that I can record my score for a game of bowling
I can start a new game 
```

``` 
As a player,
So that I can keep a record of my scores,
I want to be able to add a score for a roll
```   
``` 
As a player
So that I can view game progress
I can see the full scorecard after adding a score
``` 
``` 
As a player
So that I know where I am in the game
I can check which number frame I am currently playing
``` 
``` 
As a Player
So that I know how well I am playing
I can see my current score
```
``` 
As a Player
So that I can see when I have scored a spare (scored 10 on the second roll of a frame)
The second roll is marked with a '/' in the scorecard
The previous frame score update after next roll
```
``` 
As a Player
So that I can see when I have scored a strike (scored 10 in the first roll of a frame)
It is marked with an 'X' in the scorecard
The frame score update after every next two rolls
``` 

### Optional Extras

In any order you like:

* Create a nice interactive animated interface with jQuery.
* Set up [Travis CI](https://travis-ci.org) to run your tests.
* Add [ESLint](http://eslint.org/) to your codebase and make your code conform.

You might even want to start with ESLint early on in your work — to help you
learn Javascript conventions as you go along.

## Auther
[Shweta Patil](https://github.com/shwetzpatil)
