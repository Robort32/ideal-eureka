<img src="https://github.com/Robort32/ideal-eureka/blob/main/Robort32Logo.png">

# Group 7 - Scope Approval Outline

_Holly, Matthew & Gloria_

### Description of Project

Find something new to play with your friends because board games are awesome! Based on user provided input, app will return a selection of possible board games for you and your friends to try.

### MVP

- Landing page with a header image with app name PROJECT BORT
- Ask user for their input, re: mechanics, minimum number of players with a form
- Display board games provided by user preferences from API call from boardgameatlas.com

### Stretch Goals

- Generate random selection "I'm feeling lucky"
- Search by price
- Search by max players
- "Search again" button to clear form, reset page and allow user to search again

### Research Data

see https://api.boardgameatlas.com/api/game/categories?client_id=${apiKey}

---

## Pseudo Code

- Header and welcome instructions that our site is to find a new board game they should try by selecting options from the dropdown menus.

- at the top of the page is the header

- a form with dropdowns

  - followed by the dropdown menus and “submit” button
  - dropdown will prompt for a mechanic selection, and another to select min number of players
  - submit button

- store user selection in variables.

- make an API call to boardgameatlas.com using the users selection to search for games

- display the list of returned games, render HTML elements in grid/flexbox with game name & details.

---

## Wire Frame

**stretch goals in red**

<img src="https://github.com/Robort32/ideal-eureka/blob/main/ScopeApproval/FunPunDesktop.png" alt="wireframe desktop group 7">

<img src="https://github.com/Robort32/ideal-eureka/blob/main/ScopeApproval/FunPunMobile.png" alt="wireframe mobile group 7">
