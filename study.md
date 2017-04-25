# Game Project Scope Study

## Required Readings

-   [Game Project](https://github.com/ga-wdi-boston/game-project)
-   [Game API](https://github.com/ga-wdi-boston/game-project-api)
-   [What is a User Story](https://www.mountaingoatsoftware.com/agile/user-stories)

## Deliverables

After reading the `game-project` prompt and the `game-project-api` documentation
please do the following and be prepared to share and discuss during our next
class.

Submit detailed answers to the following in this file via a pull request:

-   A wireframe of what your game project will look like.
I have wireframe, but do not know how to add it to this .md file.

-   The data structure you plan to use.

  Data structure to be sent to API as used in class exercises.

-   How you will take the markup of the game board and represent it in JS
-
<div class="container-fluid gameboard">
  <div class="col-xs-6 col-centered">
      <div class="row">
        <div class="game gamegrid">
            <div class="row">
              <div class="col-xs-2 box square" id='s0'></div>
              <div class="col-xs-2 box square" id='s1'></div>
              <div class="col-xs-2 box square" id='s2'></div>
            </div>
            <div class="row">
              <div class="col-xs-2 box square" id='s3'></div>
              <div class="col-xs-2 box square" id='s4'></div>
              <div class="col-xs-2 box square" id='s5'></div>
            </div>
            <div class="row">
              <div class="col-xs-2 box square" id='s6'></div>
              <div class="col-xs-2 box square" id='s7'></div>
              <div class="col-xs-2 box square" id='s8'></div>
            </div>
          </div>
          </div>
        <div class="modal-footer"></div>
  </div>
</div>

-   How you plan to approach this project.

    1) Plan
    2) write curl and api calls
    3) write game logic
    4) work on UI

-   4-8 user stories for your game project.

  As a user I want to be able to create an account.
  As a user I want to be able to change my password
  As a user, I want to be able to log in.
  As a user, I want to be to log out.
  As a competitive player, I want to know my win counts.


-   How you plan to keep your code modular.
  Keep authentication and game modules seperate:
      :assets/script/auth
        Events
        UI
        API
      :assets/script/game
        Events
        UI
        API


-   What creative spin will you add to your project?
  the messages will have a little humor to them.

-   How will you use version control to backup / track your project?
  using git to commit often.

-   Do you plan to attempt any of the bonuses?
  I will be focus on fullfilling the requirements. If I have time, I will attemp the bonuses.

You may want to submit pictures for your wireframes and/or user stories.
[Markdown Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
has instructions to link to a picture you've uploaded to a service like [Imgur](http://imgur.com/).
