# Hangman

The goal of this lab is to implement an AngularJS
version of the
[Hangman](http://en.wikipedia.org/wiki/Hangman_%28game%29)
game.

## Setup

- You should create a Rails app and set up an Angular front-end.
- Most of the lab will be in Angular, but we want you get used to
  integrating it with Rails.
- This will be a single page app.

## Minimum Requirements

See the [Wikipedia](http://en.wikipedia.org/wiki/Hangman_%28game%29)
link for basic gameplay instructions if you are unfamiliar with them.

- A user should be able to enter a word and then it should be hidden
  from view.
- Each letter of the word should be represented by an underlined blank
  space.
- Another use should be able to guess letters.

    - If a letter is guessed correctly, all instances of it should be
      shown in place of the blank spaces.
    - If a guessed letter is not in the word, a counter should be
      incremented as the user is only allowed a certain number of
      guesses.
    - A user should not be able to guess the same letter twice.

- The second user wins if she correctly identifies all the letters
  before the guessing limit is reaches.

## Bonus

- To help indicate the number of remaining guesses, draw the hangman
  (or the representation of your choosing) on an HTML5 Canvas element.

- Save a history of the games played to a database via a Rails JSON API.
