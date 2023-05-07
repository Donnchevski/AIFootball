# AIFootball
Python script for 3v3 football game used in Robomac competition as part of the AI category.

## Rules
* 3 vs 3 Players football game, everyone is a player and a goalkeeper at the same time
* Match duration is 90 seconds
* Each one of the three players have the following attributes:
|mass| player mass|
|----|
|radius| player size|
|------|
|acceleration| player top acceleration|
|------------|
|speed| player top speed|
|-----|
|shopt power| player top shoot power|
|-----|
* `AIFootball.py` is the official simulation script
* You write the `dicision()` function in `Manager.py`
* You can remove the render to speed up training

## Every player has
* Mass
* Maximum acceleration
* Maximum speed
* Shot power
* Radius proportional to his height

## Your task
* Knowing the position of the ball and all the players on the field, calculate your next move
* Act with force on your players, the simulation script will take care of the position and the velocity
* If you want to shoot the ball then set the appropirate variable `shot_request` to `True`. The ball will be shot on the next collision between the player and the ball

## Good luck
