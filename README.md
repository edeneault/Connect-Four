# Connect-Four: UNIT 11 Report
<sup>by: Etienne Deneault</sup>

App URL: https://edeneault.github.io/Connect-Four/
GitHub Repository: https://github.com/edeneault/Connect-Four/tree/main

## Features

* Game Start and Reset Buttons.

* Mark-up includes Nav Bar with the buttons and persisted value scoreboard. Nav Bar is collapsable.

* Token drop is CSS Animated- *vert-slide-in* and *star-spin*.

* Local Storage is uses to persist - shortest and longest game values in the scoreboard.

* 3D CSS EyeBall integrated into the background images for "large" viewports (above width: 1320px). @Media inquiries included to remove if the user viewport is to small to support "positioning".

* Responsive Behavior - adapts to smaller viewports with the use of BootStrap4 classes and CSS @media inquiries.

## Know Issues and Furthey Study 

* Alignment of falling tokens is off on smaller screens.  Needs furthey study to fix.
* Adding difficulty settings by dynamically adjusting height and width values using user
input.  To be implememted.
* The code would benefit from utilizing more economical syntax/stucture code i.e. higher order functions and ES 2015 functions.
* As mentionened, in the project hand-out, checkForWin() could be more efficient.  I think that using a set of *array-like collections* for winning states in combination with *some* would return quickly if the state of the board has a winner.  




## Process && Learnings

* The process that I followed was the following:
    * Game design reflection: functions needed and game logic.
    * Assignment step-by-step to build basic app functionality and mark-up.
    * Addition of additional helper functions
    * Polishing of html and css
    * Commenting and Documentation

* Higher order functions and ES2015 is a challenge: My learning is not settled and I don't yet have full clarity on when and how to implement in my coding style.  Surely, this will come in time with more practice.

* Experimented with 3d capabilities of css and got some practice with css positioning. (and it's limitations when designing for responsiveness)

## Game Renderings

<div align="center">
  <img width="400px" min-height="450px" src="Connect4_Render_1.png">
  <img width="400px" min-height="700px" src="Connect4_Render_4.png">
  <img width="400px" min-height="450px"  src="Connect4_Render_3.png">
</div>


## Technologies && Third Party Libraries && Fonts

* Bootstrap4: https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css
* Google Font APi: https://fonts.googleapis.com/css?family=Bangers


## Sources && References

* Code Base provided by SpringBoard - Connect-four (Unit 11)

* Eye Ball css was adapted from the code in the following article: https://cssanimation.rocks/spheres/

* Background Image: https://wallpaperaccess.com/full/199962.jpg  (non-monitized use is explicitly stated as permitted)
