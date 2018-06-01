# Getting Started
This is my way to be a better programmer by trying to code by my own head, when I stuck I can take a peeking on the solution.
### [MDN web docs](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/A_first_splash)

# Guess the number game
### We have selected a random number between 1 and 100. See if you can guess it in 10 turns or fewer. We'll tell you if your guess was too high or too low.

# Stages

1. - [x] Generate a random number between 1 and 100.
2. - [x] Record the turn number the player is on. Start it on 1.
3. Provide the player with a way to guess what the number is.
4. Once a guess has been submitted first record it somewhere so the user can see their previous guesses.
5. Next, check whether it is the correct number.
6. If it is correct:
   - [ ] Display congratulations message.
   - [ ] Stop the player from being able to enter more guesses (this            would mess the game up).
   - [ ] Display control allowing the player to restart the game.
7. If it is wrong and the player has turns left:
   - [ ] Tell the player they are wrong.
   - [ ] Allow them to enter another guess.
   - [ ] Increment the turn number by 1.
8. If it is wrong and the player has no turns left:
   - [ ] Tell the player it is game over.
   - [ ] Stop the player from being able to enter more guesses (this would mess the game up).
   - [ ] Display control allowing the player to restart the game.
9. - [ ] Once the game restarts, make sure the game logic and UI are completely reset, then go back to step 1.
