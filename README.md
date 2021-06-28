# Play-Snake 🐍
Snake is the common name for a video game concept where the player maneuvers a line which grows in length, with the line itself being a primary obstacle.
## Prerequisite Gems <a href="https://www.ruby-lang.org" emoji-code="Ruby"><img class="emojidex-emoji" src="https://cdn.emojidex.com/emoji/mdpi/Ruby.png" emoji-code="Ruby" alt="Ruby" /></a>
 Ruby 2D - Create 2D applications, games, and visualizations with ease. 
 To install Ruby 2D, run
 `gem install ruby2d`
 
 ## Game Play 🕹
 1. The player controls a dot, square, or object on a bordered plane. As it moves forward, it leaves a trail behind, resembling a moving snake.
 In some games, the end of the trail is in a fixed position, so the snake continually gets longer as it moves.
 In another common scheme, the snake has a specific length, so there is a moving tail a fixed number of units away from the head.
 The player loses when the snake runs into the screen border, a trail, other obstacle, or itself.

The Snake concept comes in two major variants:

1. In the first, which is most often a two-player game, there are multiple snakes on the playfield.
Each player attempts to block the other so the opponent runs into an existing trail and loses.
Surround for the Atari VCS is an example of this type. The Light Cycles segment of the Tron arcade game is a single-player version where the other "snakes" are AI controlled.
2. In the second variant, a sole player attempts to eat items by running into them with the head of the snake.
Each item eaten makes the snake longer, so avoiding collision with the snake becomes progressively more difficult.

My game follows the second concept

## How to Play 🤔
Download the code first at a preferred file location.
Open Command Prompt at the file location and run
`ruby2d console snake.rb`

## Game Controls 🎮
 Use arrow keys to control the snake.
 
 Key | Movement
------------ | -------------
🡠 | Left
🡢 | Right
🡡 | Up
🡣 | Down
P  | Pause
Q  | Quit
R  | Restart

## In action
<img align="left" width="500" height="500" src="https://user-images.githubusercontent.com/75536064/123614681-2bc8ce00-d822-11eb-86c6-30c533fd6229.png">
<img align="right" width="500" height="500" src="https://user-images.githubusercontent.com/75536064/123614568-1784d100-d822-11eb-9af8-87ae7f2c7b8d.png">
<img align="left" width="500" height="500" src="https://user-images.githubusercontent.com/75536064/123614605-1fdd0c00-d822-11eb-98b8-7e1428756352.png">
<img align="right" width="500" height="500" src="https://user-images.githubusercontent.com/75536064/123614483-ffad4d00-d821-11eb-9a23-7617cd67f25b.png">



