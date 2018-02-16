Who Contributed To This Repo?
-----------------------------
- Jacob
- Dan
- Carter
- Renee

This must stop:
---------------
![Nevar again](https://i.makeagif.com/media/8-22-2014/GO_DT4.gif)


Koala Holla
===========

Our client, Koala Holla (1976 Llama Comma Drive, Walla Walla WA) is a non-profit dedicated to the ethical transitioning of koalas from the outdoors (whereupon they may be rained) to urban areas where roofs exist. Your team has been hired build a web app to handle their terrarium residents.

Technologies
------------
* JQuery
* Node
* Express
* SQL

Client needs
------------
Koala Holla has provided a table of their current inventory:

| id | name    | gender | age | ready_to_transer | notes                            |
|----|---------|--------|-----|------------------|----------------------------------|
| 1  | Scotty  | M      | 4   | Y                | Born in Guatemala                |
| 2  | Jean    | F      | 5   | Y                | Allergic to lots of lava         |
| 3  | Ororo   | F      | 7   | N                | Loves listening to Paula (Abdul) |
| 4  | Logan   | M      | 15  | N                | Loves the sauna                  |
| 5  | Charlie | M      | 9   | Y                | Favorite band is Nirvana         |
| 6  | Betsy   | F      | 4   | Y                | Has a pet iguana                 |

They want a database table that houses this information and can be viewed at any time. You should create a `koala_holla` database and add the data from the table above to a `koala` table. After adding the data, create a web app to display the Koalas. Users should be able to add new Koalas to the database through the provided HTML form.

They have also provided their logo and the source code from when Lou (a KH employee) tried to spin up a JEN stack project to support this, but had to leave for foraging school in Finland before he could finally finish. (JEN is short for jQuery, Express & Node).

Hard Mode
---
1. Ability for mark Koala ready for transfer. Add a button to each row that reads 'Ready for Transfer'. When the user clicks on the button, it should update the database for the specific Koala. The 'Ready for Transfer' button should only appear for Koalas that haven't yet been marked ready for transfer.

2. Ability to delete Koalas from the database.

3. Add some styling with bootstrap.

Pro Mode
---
1. Ability to edit information for existing Koalas in the db.
2. Ability to toggle the display of Koalas ready for transfer.
3. Add form validation, additional styling and a README.md.

Delivery
--------
Upon completion of the project you'll need to provide not only the source (via GitHub url), but also instructions on how the database table should be set up. This can be in a simple `database.sql` file in the repo.

Sample Output
--------
Your final product may look something like this:

![sample](sample.png)

# Project Planning and Management

## Base Mode
- [x] Database Table which houses information
    - [x] id
    - [x] name
    - [x] gender
    - [x] age
    - [x] ready_to_transfer
    - [x] notes
- [x] Web app that displays the database taeateble on the DOM
    - [x] User can add new Koala to database

## Hard Mode
- [x] On the DOM, user can mark a Koala for transfer
    - [x] Button for each row that reads `Ready For Transfer`
    - [x] When clicking the button, it will update the database on the specific Koala showing it is `Ready For Transfer`
    - [x] `Ready For Transfer` only appears for Koalas that haven't been marked `Ready For Transfer`
- [x] User can delete koala from the database
- [x] Add styling with bootstrap

## Pro Mode
- [ ] User can edit existing Koalas
- [ ] Create a toggle display for Koala's `Ready for Transfer`
- [ ] Add Form Validation
- [ ] Additional Styling
- [x] Create a README.md file